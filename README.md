<!-- [![View article](https://img.shields.io/badge/Data_Science_Simplified-View_article-blue)](https://mathdatasimplified.com/2023/06/17/how-to-structure-a-data-science-project-for-readability-and-transparency-2/) [![View on YouTube](https://img.shields.io/badge/YouTube-Watch%20on%20Youtube-red?logo=youtube)](https://youtu.be/TzvcPi3nsdw)  -->

# Data Science Cookie Cutter

## Why?
It is important to structure your data science project based on a certain standard so that your teammates can easily maintain and modify your project.

This repository provides a template that incorporates best practices to create a maintainable and reproducible data science project.  

## Tools used in this project
* [hydra](https://hydra.cc/): Manage configuration files - [article](https://mathdatasimplified.com/stop-hard-coding-in-a-data-science-project-use-configuration-files-instead/)
* [pdoc](https://github.com/pdoc3/pdoc): Automatically create an API documentation for your project
* [pre-commit plugins](https://pre-commit.com/): Automate code reviewing formatting
* [Rye](https://github.com/astral-sh/rye): Dependency and virtual environment management
* [DVC](https://github.com/iterative/dvc): Manage data version
* 

## How to use this project

Install Cookiecutter:
```bash
pipx install cookiecutter
```

Create a project based on the template:
```bash
cookiecutter https://github.com/mmorinag127/WonderOfU
```

## Resources for a detailed explanation of this template:
- [Article](https://mathdatasimplified.com/how-to-structure-a-data-science-project-for-readability-and-transparency-2/)
- [Video](https://youtu.be/TzvcPi3nsdw)