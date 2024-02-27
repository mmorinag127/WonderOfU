.PHONY: tests docs

install: 
	@echo "Installing dependencies..."
	# rye init {{ cookiecutter.__directory_name }}
	@echo "Rye will pin Python version" {{ cookiecutter.compatible_python_versions }}
	rye pin {{ cookiecutter.compatible_python_versions }}
	rye sync
	@echo "Initializing Git..."
	git init
	@echo "Installing pre-commit..."
	rye run pre-commit install

activate:
	@echo "Activating virtual environment"
	source .venv/bin/activate

tests:
	pytest

docs:
	@echo Save documentation to docs... 
	pdoc src -o docs --force
	@echo View API documentation... 
	pdoc src --http localhost:8080	
