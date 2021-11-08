# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test deck https://github.com/nutellinoit/asdf-deck.git "deck --help"
```

Tests are automatically run in GitHub Actions on push and PR.
