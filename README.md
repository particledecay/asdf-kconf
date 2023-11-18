<div align="center">

# asdf-kconf [![Build](https://github.com/particledecay/asdf-kconf/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/particledecay/asdf-kconf/actions/workflows/build.yml)

[kconf](https://github.com/particledecay/kconf) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add kconf
# or
asdf plugin add kconf https://github.com/particledecay/asdf-kconf
```

kconf:

```shell
# Show all installable versions
asdf list-all kconf

# Install specific version
asdf install kconf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kconf latest

# Now kconf commands are available
kconf version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/particledecay/asdf-kconf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Joey Espinosa](https://github.com/particledecay/)
