# Running fedora-review on every commit

This repository contains an action that all packages can use

## Usage

See this example project

https://github.com/FrostyX/fedora-review-ci-hello/tree/main


## Tests

This action is used by other projects' workflows. To test it locally without
pushing, use:

```
sudo dnf install act-cli
act -W .forgejo/workflows/
```
