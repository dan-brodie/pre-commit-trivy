# pre-commit-trivy
A pre-commit hook for trivy

``````
repos:
-   repo: https://github.com/dan-brodie/pre-commit-trivy.git
    rev: v0.0.1
    hooks:
    -   id: trivyinit
    -   id: trivyfs
        args:
          - .
    -   id: trivyk8
        args:
          - .
```