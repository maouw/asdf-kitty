<div align="center">

# asdf-kitty [![Build](https://github.com/maouw/asdf-kitty/actions/workflows/build.yml/badge.svg)](https://github.com/maouw/asdf-kitty/actions/workflows/build.yml) [![Lint](https://github.com/maouw/asdf-kitty/actions/workflows/lint.yml/badge.svg)](https://github.com/maouw/asdf-kitty/actions/workflows/lint.yml)

[kitty](https://github.com/kovidgoyal/kitty) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add kitty
# or
asdf plugin add kitty https://github.com/maouw/asdf-kitty.git
```

kitty:

```shell
# Show all installable versions
asdf list-all kitty

# Install specific version
asdf install kitty latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kitty latest

# Now kitty commands are available
kitty --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/maouw/asdf-kitty/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Altan Orhon](https://github.com/maouw/)
