# TeraSky OSS Homebrew tap

```console
brew tap terasky-oss/tap
```

## convctl

CLI for the [declarative-conversion-operator](https://github.com/TeraSky-OSS/declarative-conversion-operator)
— validate, test and diff Crossplane XRD / CRD conversion configs offline.

```console
brew install --cask terasky-oss/tap/convctl
```

Casks are **published automatically** by the operator's release workflow
(GoReleaser). Do not edit `Casks/` by hand — the next release overwrites it.

macOS will warn on first run: these binaries are checksummed and
cosign-signed, but not Apple-notarized. See the release notes for
verification commands.
