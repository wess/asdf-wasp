<div align="center">

# asdf-wasp 
[Wasp](https://wasp-lang.dev) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wasp
# or
asdf plugin add wasp https://github.com/wess/asdf-wasp.git
```

Wasp:

```shell
# Show all installable versions
asdf list-all wasp

# Install specific version
asdf install wasp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wasp latest

# Now Wasp commands are available
wasp version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/wess/asdf-wasp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Your Name](https://github.com/wess/)
