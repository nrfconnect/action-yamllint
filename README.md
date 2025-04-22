# action-yamllint
GitHub action to run `ibiqlik/action-yamllint` with a predefined set of rules on all yml/yaml files in a repo

## usage
```yaml
name: Lint yaml files
on:
  pull_request:

jobs:
  lint_yml:
    runs-on: ubuntu-latest
    steps:
      - name: Execute yamllint
        uses: nrfconnect/action-yamllint@main
```
