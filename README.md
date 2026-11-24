# Edenware Scoop bucket

Manifests for [Scoop](https://scoop.sh), maintained by [Edenware](https://edenware.app).

## Usage

```powershell
scoop bucket add edenware https://github.com/EdenwareApps/scoop-bucket
scoop install edenware/megacubo edenware/snapaway edenware/sonicaura
```

## Available manifests

| App | Version | Description |
| --- | --- | --- |
| `megacubo` | 17.8.0 | Open-source (GPL-3.0) IPTV player for live TV streaming: M3U and Xtream playlists, EPG, recording, miniplayer. |
| `snapaway` | 1.2.6 | Hide only the windows you choose from screen, taskbar and Alt+Tab with one hotkey, and bring them back instantly. |
| `sonicaura` | 1.0.6 | Audio-reactive auras drawn above the Windows desktop from whatever audio your PC is playing. |

Updates follow the vendors' own release feeds, so `scoop update` picks up new versions once the
manifest is refreshed here. The archives installed by this bucket are the vendor's portable builds
and do not include the optional Bright SDK component that the Megacubo website downloader bundles.

## Why a separate bucket

The `ScoopInstaller/Extras` bucket requires a project to be "reasonably well-known and widely used"
(roughly 100+ stars or 50+ forks) and prefers open source, so SnapAway and SonicAura do not qualify
there. This bucket is the supported install path for those apps.

## Other channels

- winget: `Edenware.Megacubo`, `Edenware.SnapAway`, `Edenware.SonicAura` (pending review in `microsoft/winget-pkgs`)
- Chocolatey: `choco install megacubo`, `choco install snapaway`, `choco install sonicaura`
- itch.io: https://edenware.itch.io