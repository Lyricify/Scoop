# Lyricify Scoop Bucket

A small [Scoop](https://scoop.sh) bucket for installing [Lyricify](https://lyricify.app) from the official [WXRIW/Lyricify-App](https://github.com/WXRIW/Lyricify-App) GitHub releases.

## Usage

```powershell
scoop bucket add lyricify https://github.com/Lyricify/Scoop
scoop install lyricify
```

For local testing before publishing:

```powershell
scoop install C:\Users\sheng.fan\Projects\Lyricify-Scoop\bucket\lyricify.json
```

## Manifests

| Manifest | App | Source |
| --- | --- | --- |
| `lyricify` | Lyricify 4 for Spotify | `WXRIW/Lyricify-App` |

The manifest uses Lyricify's self-contained portable archives so the .NET Desktop Runtime 6 dependency is bundled with the application.
