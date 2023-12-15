# GitHub Action for `python`

GitHub Action for `python` based repositories. It uses `poetry` as package manager.

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Actions

### action: [`lint`](./lint)

Lint will run pre-commit linters against the consumer repository, optionally checking out to to the consumer repository.

See usage [here](./lint/README.md#usage).

Documentation is found [here](./lint/README.md).

### action: [`test`](./test)

Test will run tests in the consumer repository using [pytest](https://github.com/pytest-dev/pytest). This action will also check out the repository if `checkout-repo` is passed, as well as `pip install .[dev]` and `pip install .[test]` for dependencies.

See usage [here](./test/README.md#usage).

Documentation is found [here](./test/README.md).

### action: [`release`](./release)

Release will optionally checkout the consumer repository and attempt a [Semantic Release](https://semantic-release.gitbook.io/semantic-release/usage/configuration) using the root level configuration file (e.g. .releaserc.json) indicating branches and plugins to use to facilitate the release.

See usage [here](./release/README.md#usage).

Documentation is found [here](./release/README.md).

## black

## flake8

[Flake8](https://flake8.pycqa.org/en/latest/): Your Tool For Style Guide
flake8 path/to/code/to/check.py

## Lint GitHub Actions workflow file Docker

actionlint-docker

## pre-commit

Run against all the files
it's usually a good idea to run the hooks against all of the files when adding new hooks (usually pre-commit will only run on the changed files during git hooks)
[https://pre-commit.com/](https://pre-commit.com/)

pre-commit run --all-files

pre-commit autoupdate

## shellcheck

pip install shellcheck-py

## Get Help

Each Action has a detailed README for how to use it as referenced above. Please review Issues, post new Issues against this repository as needed.

## Contributions

Please see [here](https://github.com/python) for guidelines on how to contribute to this project.

![](blackAndFlake8.webp)

    Linting your code with flake8, isort, and mypy.
    Formatting your code with black.
    Pre-commit Git hooks
    Automating Git formatter hooks in place.
