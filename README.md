# pre-commit-statix

Lints Nix files using [statix](https://github.com/NerdyPepper/statix).

This is an unofficial pre-commit hook to use until this [PR](https://github.com/nerdypepper/statix/pull/81) gets merged.

## Installation

This hook is meant to be used with [pre-commit](https://pre-commit.com/).

Add the following hook to `.pre-commit-config.yaml`:

```yaml
  - repo: https://github.com/fidgetingbits/pre-commit-statix
    rev: v1.0.0
    hooks:
      - id: statix-check
```

If you want to automatically fix the code, use `static-fix` id instead.

## License

Copyright © 2024 fidgetingbits

Unless otherwise specified, files in this repository are licensed under
the MIT license; see [LICENSE.md](LICENSE.md) for more information.
