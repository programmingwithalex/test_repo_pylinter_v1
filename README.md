# test_repo_pylinter

Copyright (c) 2021, [programmingwithalex](https://github.com/programmingwithalex)

## Description

Demo repo to accompany YouTube video demonstrating how to use the [`pylinter`](https://github.com/marketplace/actions/pylinter) GitHub action.

Python linting packages covered:

* `flake8`
* `mypy`
* `isort`

## Contents

* `main.py`
  * only `.py` file
  * contains obvious `mypy`, `flake8`, and `isort` errors
* `.github/workflows/main.py`
  * GitHub workflow file that uses the GitHub action [`pylinter`](https://github.com/marketplace/actions/pylinter)
  * can be used as is, or can be customized with the various flags for [`pylinter`](https://github.com/marketplace/actions/pylinter)
  * can also add/remove the last two code sections that will automatically commit and push the code changes made by `isort` (more documentation is on the [`pylinter`](https://github.com/marketplace/actions/pylinter) page)
