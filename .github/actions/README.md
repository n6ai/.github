# GitHub Actions

> Reusable quick GitHub Actions

## Example Usage

```yml
name: Release Commit

on:
  workflow_dispatch:

jobs:
  release-commit:
    runs-on: ubuntu-latest
    steps:
      - uses: n6ai/.github/.github/actions/release-commit@main
        with:
          use-bumpfile: true
```
