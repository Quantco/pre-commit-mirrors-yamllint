# yamllint pre-commit hook

pre-commit hook of yamllint with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For yamllint: see [here](https://github.com/adrienverge/yamllint)

## Using yamllint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-yamllint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: yamllint-conda
```
