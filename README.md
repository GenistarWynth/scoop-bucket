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
| [ccline](bucket/ccline.json) | CCometixLine - Claude Code statusline tool (Rust) |
| [clawd-on-desk](bucket/clawd-on-desk.json) | Pixel desktop pet that watches AI coding agents |

Only apps that scoop can genuinely manage (portable install, versioned, auto-updatable)
live here. Self-updating ecosystem apps (Steam, etc.) are handled by winget instead.

## Auto-update

Manifests are kept up to date daily by [Excavator](.github/workflows/excavator.yml)
([ScoopInstaller/GithubActions](https://github.com/ScoopInstaller/GithubActions)).
