<div align="center">

# asdf-helper-plugin [![Build](https://github.com/ngyewch/asdf-helper-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/ngyewch/asdf-helper-plugin/actions/workflows/build.yml) [![Lint](https://github.com/ngyewch/asdf-helper-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/ngyewch/asdf-helper-plugin/actions/workflows/lint.yml)


[asdf-helper](https://github.com/ngyewch/asdf-helper) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `unzip`, `git`

# Install

Plugin:

```shell
asdf plugin add asdf-helper https://github.com/ngyewch/asdf-helper-plugin.git
```

asdf-helper:

```shell
# Show all installable versions
asdf list-all asdf-helper

# Install specific version
asdf install asdf-helper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global asdf-helper latest

# Now asdf-helper commands are available
asdf-helper version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ngyewch/asdf-helper-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Ng](https://github.com/ngyewch/)
