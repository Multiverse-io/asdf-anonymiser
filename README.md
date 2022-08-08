<div align="center">

# asdf-anonymiser [![Build](https://github.com/danturn/asdf-anonymiser/actions/workflows/build.yml/badge.svg)](https://github.com/danturn/asdf-anonymiser/actions/workflows/build.yml) [![Lint](https://github.com/danturn/asdf-anonymiser/actions/workflows/lint.yml/badge.svg)](https://github.com/danturn/asdf-anonymiser/actions/workflows/lint.yml)


[anonymiser](https://github.com/Multiverse-io/anonymiser) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add anonymiser
# or
asdf plugin add anonymiser https://github.com/danturn/asdf-anonymiser.git
```

anonymiser:

```shell
# Show all installable versions
asdf list-all anonymiser

# Install specific version
asdf install anonymiser latest

# Set a version globally (on your ~/.tool-versions file)
asdf global anonymiser latest

# Now anonymiser commands are available
anonymiser --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/danturn/asdf-anonymiser/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Daniel Turner](https://github.com/danturn/)
