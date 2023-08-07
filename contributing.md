# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test rtx-helper https://github.com/ngyewch/rtx-helper-plugin.git "rtx-helper version"
```

Tests are automatically run in GitHub Actions on push and PR.
