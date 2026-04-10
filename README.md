# scoop-sct

[Scoop](https://scoop.sh) bucket for [`sct`](https://github.com/pacharanero/sct)
— the local-first SNOMED CT toolchain.

## Install

```powershell
scoop bucket add sct https://github.com/pacharanero/scoop-sct
scoop install sct
```

## Update

```powershell
scoop update
scoop update sct
```

## Uninstall

```powershell
scoop uninstall sct
scoop bucket rm sct
```

## Supported platforms

- Windows x86_64

macOS and Linux users: see [`homebrew-sct`](https://github.com/pacharanero/homebrew-sct)
for the Homebrew tap, or use the shell installer:

```bash
curl -fsSL https://raw.githubusercontent.com/pacharanero/sct/main/install.sh | sh
```

## Manifest updates

The `bucket/sct.json` manifest in this repo is updated automatically by the
[release workflow](https://github.com/pacharanero/sct/actions) in the main
`sct` repository whenever a new `v*` tag is pushed. Scoop's built-in
`checkver` / `autoupdate` mechanism can also pick up new releases without
any manual intervention.
