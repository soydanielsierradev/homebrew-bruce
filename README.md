# homebrew-bruce

Homebrew tap for [Bruce](https://github.com/soydanielsierradev/bruce-tui) — a
terminal workspace for Claude Code.

## Install

```sh
brew install soydanielsierradev/bruce/bruce
```

Or tap first, then install:

```sh
brew tap soydanielsierradev/bruce
brew install bruce
```

Bruce runs the Claude Code CLI inside its workspace, so make sure `claude` is on
your `PATH`: <https://docs.claude.com/claude-code>

## Updating the formula

On each Bruce release, copy the formula from the main repo
(`packaging/homebrew/bruce.rb`) into `Formula/bruce.rb` here — it already has the
new version and SHA256 sums.
