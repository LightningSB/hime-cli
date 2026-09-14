# hime CLI

The `hime` command-line tool connects AI agents (Claude Code, Codex, scripts) to your [Hime](https://hime.ai).
This repository only hosts release binaries.

## Install

macOS or Linux, arm64 or x64:

```sh
curl -fsSL https://github.com/LightningSB/hime-cli/releases/latest/download/install.sh | sh
```

It downloads the binary for your platform, checks it against `SHA256SUMS`, and installs it to `~/.hime/bin/hime`.
Run the same command again to upgrade. To uninstall, delete `~/.hime/bin` (your sign-in lives in `~/.hime/credentials.json`).

## Sign in

In the Hime app, open **Agent access → Create setup command**, copy it, and run it where your agent works.
It installs the CLI and signs in in one step. Then:

```sh
~/.hime/bin/hime whoami
~/.hime/bin/hime --help
```
