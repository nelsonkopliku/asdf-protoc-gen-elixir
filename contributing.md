# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test protoc-gen-elixir https://github.com/nelsonkopliku/asdf-protoc-gen-elixir.git "protoc-gen-elixir --help"
```

Tests are automatically run in GitHub Actions on push and PR.
