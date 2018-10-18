bandit mirror
===========

Mirror of bandit for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For bandit: see https://github.com/PyCQA/bandit

### Using bandit with pre-commit:

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/KPilnacek/mirrors-bandit
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: bandit
```


By default, bandit will run with `bandit -lll`.
