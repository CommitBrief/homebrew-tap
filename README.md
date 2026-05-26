# CommitBrief Homebrew Tap

Homebrew formula for [CommitBrief](https://github.com/CommitBrief/commitbrief) —
the LLM-powered local code review CLI for git diffs.

## Install

```sh
brew tap CommitBrief/tap
brew install commitbrief
```

Then run `commitbrief setup` to configure your provider and API key.

## How this repository works

This tap is **populated automatically** by
[goreleaser](https://goreleaser.com/) on every public CommitBrief release.
Do not edit `Formula/commitbrief.rb` by hand — your changes will be
overwritten on the next tag push. See the [release pipeline source][rel].

[rel]: https://github.com/CommitBrief/commitbrief/blob/main/.github/workflows/release.yml

## Reporting issues

CLI bugs and feature requests belong in the main
[commitbrief issue tracker](https://github.com/CommitBrief/commitbrief/issues).

Open issues here only for tap-specific problems (e.g. the formula is
broken or stale).

## License

The CommitBrief CLI is [GPL-3.0-or-later](https://github.com/CommitBrief/commitbrief/blob/main/LICENSE).
This tap repository contains only build metadata and is licensed the
same way.
