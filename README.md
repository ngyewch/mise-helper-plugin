<div align="center">

# rtx-helper-plugin [![Build](https://github.com/ngyewch/rtx-helper-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/ngyewch/rtx-helper-plugin/actions/workflows/build.yml) [![Lint](https://github.com/ngyewch/rtx-helper-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/ngyewch/rtx-helper-plugin/actions/workflows/lint.yml)


[rtx-helper](https://github.com/ngyewch/rtx-helper) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add rtx-helper https://github.com/ngyewch/rtx-helper-plugin.git
```

rtx-helper:

```shell
# Show all installable versions
asdf list-all rtx-helper

# Install specific version
asdf install rtx-helper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rtx-helper latest

# Now rtx-helper commands are available
rtx-helper version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ngyewch/rtx-helper-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Ng](https://github.com/ngyewch/)
