# Edenware Scoop bucket

Manifests for [Scoop](https://scoop.sh), maintained by [Edenware](https://edenware.app).

## Usage

```powershell
scoop bucket add edenware https://github.com/EdenwareApps/scoop-bucket
scoop install edenware/megacubo
```

## Available manifests

| App | Description |
| --- | --- |
| `megacubo` | Open-source IPTV player for live TV streaming (M3U, EPG, recording, miniplayer). |

Updates are detected from the vendor's PAD file (`https://megacubo.tv/pad.xml`), so `scoop update`
picks up new versions automatically.

The archives installed here are the vendor's portable builds and do not include the optional Bright
SDK component that the website downloader bundles.
