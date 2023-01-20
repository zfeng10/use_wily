## Using Wily in Github Actions

Include `wily.yml` in your repo's `./github/workflows`. Wily will check code complexity metrics and generate comments whenever there is a new pull request.


## Using Wily as a pre-commit plugin

Include `.pre-commit-config.yaml` in your repo's root directory. Follow the steps below to install and set up pre-commit hook.

```
pip install pre-commit
pre-commit install
```
