[![CI](https://github.com/gruntwork-io/asdf-terragrunt/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/gruntwork-io/asdf-terragrunt/actions/workflows/ci.yml)

# asdf-terragrunt

[Terragrunt](https://github.com/gruntwork-io/terragrunt) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.
Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions.

### Install

```
asdf plugin-add terragrunt https://github.com/ohmer/asdf-terragrunt
```

### Environment Variable Options

- `ASDF_TERRAGRUNT_OVERWRITE_ARCH`: Force the plugin to use a specified processor architecture rather than the
  automatically detected value. Useful, for example, for allowing users on M1 Macs to install `amd64` binaries when
  there's no `arm64` binary available.

- `ASDF_TERRAGRUNT_SKIP_CHECKSUM`: Skip the checksum verification when downloading the binary. This is saves some time,
  but is less secure.

### Special Thanks

This plugin was started by the community, and is now maintained by Gruntwork.

Thanks to [lotia](https://github.com/lotia) for creating the original plugin, and to [ohmer](https://github.com/ohmer) for maintaining it afterwards.

