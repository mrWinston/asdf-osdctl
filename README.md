<div align="center">

# asdf-osdctl [![Build](https://github.com/mrWinston/asdf-osdctl/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-osdctl/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-osdctl/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-osdctl/actions/workflows/lint.yml)


[osdctl](https://github.com/openshift/osdctl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add osdctl
# or
asdf plugin add osdctl https://github.com/mrWinston/asdf-osdctl.git
```

osdctl:

```shell
# Show all installable versions
asdf list-all osdctl

# Install specific version
asdf install osdctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global osdctl latest

# Now osdctl commands are available
osdctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-osdctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marius Schulz](https://github.com/mrWinston/)
