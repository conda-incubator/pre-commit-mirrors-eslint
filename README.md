# eslint pre-commit hook

Hook for eslint with conda as a language.

- For pre-commit: see https://github.com/pre-commit/pre-commit
- For eslint: see https://github.com/eslint/eslint

### Using prettier with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/Quantco/pre-commit-mirrors-eslint
  rev: "" # The git sha / tag you want to point to
  hooks:
    - id: eslint-conda
```
