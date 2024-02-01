# eslint pre-commit hook

pre-commit hook of eslint with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For eslint: see [here](https://github.com/eslint/eslint)

## Using eslint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-eslint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: eslint-conda
```
