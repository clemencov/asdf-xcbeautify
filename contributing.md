# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test xcbeautify https://github.com/clemencov/asdf-xcbeautify.git "xcbeautify --version"
```

Tests are automatically run in GitHub Actions on push and PR.
