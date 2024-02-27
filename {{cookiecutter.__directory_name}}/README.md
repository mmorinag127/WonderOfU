# {{cookiecutter.project_name}}

## Tools used in this project
* [hydra](https://hydra.cc/): Manage configuration files - [article](https://mathdatasimplified.com/stop-hard-coding-in-a-data-science-project-use-configuration-files-instead/)
* [pdoc](https://github.com/pdoc3/pdoc): Automatically create an API documentation for your project
* [pre-commit plugins](https://pre-commit.com/): Automate code reviewing formatting
* [Rye](https://github.com/astral-sh/rye): Dependency and virtual environment management
* [DVC](Data version control): Manage data version

## Project Structure

```shell
./
├── .gitignore                     # git ignore
├── .pre-commit-config.yaml        # config file for pre commit
├── config                         # config dir
│  ├── data                        #  for training model
│  ├── main.yaml                   # Main configuration file
│  └── model                       # for model parameters
├── data                           
│  ├── final                       # data after training model
│  ├── processed                   # data after processing
│  └── raw                         # raw data
├── docs                           # documentation for this project
├── Makefile                       # store useful commands to setup the environment
├── models                         # store models
├── notebooks                      # store notebooks
├── pyproject.toml                 # configure all depenency for this project
├── README.md                      # README
├── reports                        # store files for reporting task
│  └── figures                     # 
├── src                            # source files
│  ├── data                        #  for data processing
│  ├── models                      #  for model
│  └── visualization               #  for visualization
└── tests                          # store tests
```


## Set up the environment


## Auto-generate API documentation

To auto-generate API document for your project, run:

```bash
make docs
```
