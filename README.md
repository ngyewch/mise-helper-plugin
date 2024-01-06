<div align="center">

# mise-helper-plugin [![Build](https://github.com/ngyewch/mise-helper-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/ngyewch/mise-helper-plugin/actions/workflows/build.yml) [![Lint](https://github.com/ngyewch/mise-helper-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/ngyewch/mise-helper-plugin/actions/workflows/lint.yml)


[mise-helper](https://github.com/ngyewch/mise-helper) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add mise-helper https://github.com/ngyewch/mise-helper-plugin.git
```

mise-helper:

```shell
# Show all installable versions
asdf list-all mise-helper

# Install specific version
asdf install mise-helper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mise-helper latest

# Now mise-helper commands are available
mise-helper version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ngyewch/mise-helper-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Ng](https://github.com/ngyewch/)
