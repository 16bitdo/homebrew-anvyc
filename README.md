# homebrew-anvyc

Homebrew tap for [anvyc](https://github.com/16bitdo/anvyc) — macOS CLI to
safely back up, compare, restore, and synchronize developer tool
configurations across machines.

## Install

```bash
brew tap 16bitdo/anvyc
brew install anvyc
anvyc --version
```

## Source-of-truth

The `Formula/anvyc.rb` here is a copy of the canonical version at
[16bitdo/anvyc/packaging/homebrew/Formula/anvyc.rb](https://github.com/16bitdo/anvyc/blob/main/packaging/homebrew/Formula/anvyc.rb).
The release procedure that keeps both in sync is documented in
[docs/homebrew-publishing.md](https://github.com/16bitdo/anvyc/blob/main/docs/homebrew-publishing.md).

## Currently published

- anvyc v0.7.1 (sdist sha256 verified against GitHub Release `SHA256SUMS`)

## License

The Formula itself is MIT (same as anvyc).
