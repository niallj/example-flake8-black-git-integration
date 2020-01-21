Following the instructions at: https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/

1. Create and activate a virtualenv `python -m venv env && source env/bin/activate`
2. Install `pre-commit` and add to requirements.txt
3. Update .pre-commit-config.yaml
4. Execute `pre-commit install`

The following files in this repo control the two linters:
* pyproject.toml (used by black)
* .flake8 
