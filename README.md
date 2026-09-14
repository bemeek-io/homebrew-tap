# Homebrew tap for Pando

```bash
brew install bemeek-io/tap/pando
```

Pando deploys applications to a host you own. Source, issues and documentation are at
[bemeek-io/pando](https://github.com/bemeek-io/pando).

This installs the Pando CLI. The Pando server is installed with the project's Compose file, which
supplies the Postgres it needs; a package manager does not.

On Linux the same command needs Homebrew 4.5 or newer, which is where cask support arrived. On
anything older, use the `.deb`, `.rpm` or `.apk` on the
[releases page](https://github.com/bemeek-io/pando/releases).

## About this repository

`Casks/pando.rb` is written by GoReleaser when a release is tagged in the main repository, and is
overwritten on every release. Do not edit it by hand — changes belong in `.goreleaser.yaml` in
[bemeek-io/pando](https://github.com/bemeek-io/pando).
