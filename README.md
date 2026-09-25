# wdremington/homebrew-tap

Homebrew casks for [TokenCounter](https://github.com/wdremington/claude-token-counter).

```sh
brew install --cask wdremington/tap/tokencounter
```

## Maintenance

This tap is the only copy of the cask. When `claude-token-counter` publishes a
release, the **Autobump** workflow (daily, or run it by hand from the Actions
tab) opens a PR that updates `version` and `sha256`. CI then checks the cask
with `brew style`, `brew audit`, and an install/uninstall with a Gatekeeper
check. Merge the PR once CI is green.
