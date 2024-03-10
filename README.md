# autoformat-org-mode
Automatically format org-mode files with go-org package.

## Installation

## Use with pre-commit

To run `go-org` autoformat as part of a [pre-commit][pre-commit] workflow, add something like the below to the `repos` list in the project's `.pre-commit-config.yaml`:

```yaml
  - repo: https://github.com/OliverTED/autoformat-org-mode
    rev: v1.7.0
    hooks:
      - id: org-mode-autoformat
        args: [--fix]
```

## Related

- [go-org][go-org] - the original go code for formatting org files
- [pre-commit][pre-commit] - pre-commit framework for automatic actions on commits

## License

MIT © Oliver Burghard

[go-org]: https://github.com/niklasfasching/go-org
[pre-commit]: https://pre-commit.com/
