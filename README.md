[![Build Status](https://github.com/ohmer/asdf-terragrunt/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ohmer/asdf-terragrunt/actions/workflows/ci.yml)

# asdf-terragrunt

Originally from https://github.com/lotia/asdf-terragrunt where it no longer appears to be maintained.

[Terragrunt](https://github.com/gruntwork-io/terragrunt) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.
Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions.

### Install

```
asdf plugin-add terragrunt https://github.com/ohmer/asdf-terragrunt
```

### Environment Variable Options

- `ASDF_TERRAGRUNT_OVERWRITE_ARCH`: force the plugin to use a specified processor architecture rather than the
  automatically detected value. Useful, for example, for allowing users on M1 Macs to install `amd64` binaries when
  there's no `arm64` binary available.
