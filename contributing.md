# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test powerpipe https://github.com/vthiery/asdf-powerpipe.git "powerpipe --version"
```

Tests are automatically run in GitHub Actions on push and PR.
