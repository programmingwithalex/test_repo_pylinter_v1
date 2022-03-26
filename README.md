# test_repo_pylinter

Copyright (c) 2021, [programmingwithalex](https://github.com/programmingwithalex)

## Description

Demo repo to accompany YouTube video demonstrating how to use the [`pylinters GitHub action`](https://github.com/marketplace/actions/pylinters).

## Contents

* `main.py`
  * only `.py` file
  * contains obvious `mypy`, `flake8`, and `isort` errors
* `.github/workflows/main.py`
  * GitHub workflow file that uses the GitHub action [`pylinters`](https://github.com/marketplace/actions/pylinters)
  * can be used as is, or can be customized with the various flags for [`pylinters`](https://github.com/marketplace/actions/pylinters)
  * can also add/remove the last two code sections that will automatically commit and push the code changes made by `isort` (more documentation is on the [`pylinters`](https://github.com/marketplace/actions/pylinters) page)

## ENV Vars

* `GH_ACCESS_TOKEN`
  * [Reference](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token)
  * Necessary to auto-commit/push `isort` changes
