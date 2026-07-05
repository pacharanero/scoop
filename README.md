# scoop

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

## Manifest updates

The `bucket/sct.json` manifest in this repo is updated automatically by the
[release workflow](https://github.com/pacharanero/sct/actions) in the main
`sct` repository whenever a new `v*` tag is pushed. Scoop's built-in
`checkver` / `autoupdate` mechanism can also pick up new releases without
any manual intervention.
