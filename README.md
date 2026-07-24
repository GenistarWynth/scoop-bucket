# scoop-bucket

Personal [Scoop](https://scoop.sh/) bucket by [GenistarWynth](https://github.com/GenistarWynth).

## Usage

```powershell
scoop bucket add GenistarWynth https://github.com/GenistarWynth/scoop-bucket
scoop install GenistarWynth/<app>
```

## Apps

| App | Description |
| --- | --- |
| [bettbox](bucket/bettbox.json) | Mihomo (Clash) GUI client |
| [steam](bucket/steam.json) | Valve game platform client (requires admin terminal; installs to Program Files) |

## Auto-update

Manifests are kept up to date daily by [Excavator](.github/workflows/excavator.yml)
([ScoopInstaller/GithubActions](https://github.com/ScoopInstaller/GithubActions)).
