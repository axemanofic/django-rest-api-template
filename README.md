# django-rest-api-template

> A template with "basic" (in my personal opinion) dependencies, for developing a REST API on the Django framework.

## Content

* What modules are installed?
* Install poetry
  * osx / linux / bashonwindows install instructions
  * Windows powershell install instructions
  * Small project setup
* Installing dependencies via pip

##  What modules will be installed?

| Module | Version |
| ------ | ------- |
| [Django](https://docs.djangoproject.com/en/4.0/) | ^4.0.3 |
| [Django Rest Framework](https://www.django-rest-framework.org/) | ^3.13.1 |
| [django-cors-headers](https://github.com/adamchainz/django-cors-headers) | ^3.11.0 |
| [drf-yasg](https://drf-yasg.readthedocs.io/en/stable/index.html) | ^1.20.0 |

## Install Poetry

### osx / linux / bashonwindows install instructions

```shell
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

### Windows powershell install instructions
```
(Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python -
```

Read Poetry documentation [here](https://python-poetry.org/docs/)

### Small project setup

```sh
# Create the virtualenv inside the project’s root directory.
poetry config virtualenvs.in-project true

# Install the dependencies only, run the install command with the --no-root flag
poetry install --no-root
```

## Installing dependencies via pip

---

Along with the project comes a 'requirements.txt' dependency file created by Poetry. If you don't like Poetry use it.