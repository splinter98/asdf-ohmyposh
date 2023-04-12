<div align="center">

# asdf-ohmyposh [![Build](https://github.com/splinter98/asdf-ohmyposh/actions/workflows/build.yml/badge.svg)](https://github.com/splinter98/asdf-ohmyposh/actions/workflows/build.yml) [![Lint](https://github.com/splinter98/asdf-ohmyposh/actions/workflows/lint.yml/badge.svg)](https://github.com/splinter98/asdf-ohmyposh/actions/workflows/lint.yml)


[ohmyposh](https://github.com/splinter98/asdf-ohmyposh) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ohmyposh
# or
asdf plugin add ohmyposh https://github.com/splinter98/asdf-ohmyposh.git
```

ohmyposh:

```shell
# Show all installable versions
asdf list-all ohmyposh

# Install specific version
asdf install ohmyposh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ohmyposh latest

# Now ohmyposh commands are available
oh-my-posh --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/splinter98/asdf-ohmyposh/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stephen Alderman](https://github.com/splinter98/)
