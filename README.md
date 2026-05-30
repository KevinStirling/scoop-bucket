# scoop-bucket

A [Scoop](https://scoop.sh/) bucket for my personal Windows packages.

## Installation

First, install Scoop if you haven't already:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

Add this bucket:

```powershell
scoop bucket add kevinstirling https://github.com/KevinStirling/scoop-bucket
```

Then install any package from the bucket:

```powershell
scoop install kevinstirling/<package>
```

## Available packages

| Package | Description |
| --- | --- |
| [scorebug](scorebug.json) | Live MLB scores in your terminal |

### scorebug

```powershell
scoop install kevinstirling/scorebug
```

## Updating

To update an installed package to the latest version published in this bucket:

```powershell
scoop update
scoop update <package>
```

## License

[MIT](LICENSE)
