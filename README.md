# python-ddd
Domain-Driven Design Python Application boilerplate.

## Getting started

This template includes Python 3.11 support and Poetry for dependency management. Also the following packages:

* `pytest` as testing framework.
* `black` for formatting your code.
* `flake8` for style and quality checks.
* `mypy` for static typying.
* `pre-commit` for glueing all together.

### Install

Make sure you have Poetry install, and clone this repository. Then just run:

```shell
poetry install
```

And start adding your code.

## File structure


```pre
  ── src
      ├── application
      │   └── __init__.py
      ├── domain
      │   ├── __init__.py
      │   ├── entities.py
      │   ├── repositories.py
      │   └── value_objects.py
      └── infrastructure
          └── __init__.py
```
