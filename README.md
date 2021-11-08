<div align="center">

# asdf-deck [![Build](https://github.com/nutellinoit/asdf-deck/actions/workflows/build.yml/badge.svg)](https://github.com/nutellinoit/asdf-deck/actions/workflows/build.yml) [![Lint](https://github.com/nutellinoit/asdf-deck/actions/workflows/lint.yml/badge.svg)](https://github.com/nutellinoit/asdf-deck/actions/workflows/lint.yml)


[deck](https://docs.konghq.com/deck/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add deck
# or
asdf plugin add deck https://github.com/nutellinoit/asdf-deck.git
```

deck:

```shell
# Show all installable versions
asdf list-all deck

# Install specific version
asdf install deck latest

# Set a version globally (on your ~/.tool-versions file)
asdf global deck latest

# Now deck commands are available
deck --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nutellinoit/asdf-deck/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Samuele Chiocca](https://github.com/nutellinoit/)
