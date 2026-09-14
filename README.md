# Bemeek's Homebrew tap

Casks for Bemeek's tools. macOS, and Linux with Homebrew 4.5 or newer, which is where cask support
arrived.

## Pando

Deploy applications to a host you own.

```bash
brew install bemeek-io/tap/pando
```

This installs the Pando CLI. The Pando server is installed with the project's Compose file, which
supplies the Postgres it needs; a package manager does not. Source, issues and documentation are at
[bemeek-io/pando](https://github.com/bemeek-io/pando).

On an older Homebrew, or on a machine without one, use the `.deb`, `.rpm`, `.apk` or the tarball on
the [releases page](https://github.com/bemeek-io/pando/releases).

## About this repository

Every cask here is written by GoReleaser when a release is tagged in the tool's own repository, and
is overwritten by the next release. Nothing in this repository is edited by hand — a change to how a
cask is built belongs in that tool's `.goreleaser.yaml`.
