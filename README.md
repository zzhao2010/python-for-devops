[![Test Multiple Python Versions](https://github.com/zzhao2010/python-for-devops/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/zzhao2010/python-for-devops/actions/workflows/main.yml)

# python-for-devops

From zero repository for doing Python DevOps work

## Create a project scaffold

- Create development environment that is cloud-based

### Colab Notebook

- This is an example of how to use [colab](https://github.com/zzhao2010/python-for-devops/blob/main/getting_started_python.ipynb)

### GitHub Codespaces

Build out Python project scaffold:

- [Makefile](https://github.com/zzhao2010/python-for-devops/blob/main/Makefile)
- [requirements.txt](https://github.com/zzhao2010/python-for-devops/blob/main/requirements.txt)
- [test_lib.py](https://github.com/zzhao2010/python-for-devops/blob/main/test_devopslib.py)
- [python_lib](https://github.com/zzhao2010/python-for-devops/tree/main/devopslib)
- Dockerfile
- command-line tool
- Microservice

1. Create a [virtualenv](https://stackoverflow.com/questions/41573587/what-is-the-difference-between-venv-pyvenv-pyenv-virtualenv-virtualenvwrappe): `virtualenv ~/.venv` OR `python3 -m venv ~/.venv`

2. edit ~/.bashrc: `source ~/.venv/bin/activate`

3. Make sure the env is clean: `pip freeze | wc -l`

4. Explicitly list the required libs in [requirements](https://github.com/zzhao2010/python-for-devops/blob/main/requirements.txt)

5. Define the [Makefile](https://github.com/zzhao2010/python-for-devops/blob/main/Makefile) and then run `make install`

6. Find the required libs with version and pin them in the [requirements](https://github.com/zzhao2010/python-for-devops/blob/main/requirements.txt)

## Command-Line Tools

Command-Line tool provide a simple way to try different combinations of your code before building containerized microservice.

![image](https://user-images.githubusercontent.com/63174713/197016803-83c965be-2686-4dfc-a739-502708a60a9b.png)

[Python Fire](https://github.com/google/python-fire)

## Microservices

## Containerized Continuous Delivery

`docker run -p 127.0.0.1:8050:8050 23ae08944771`
