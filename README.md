# Lyricify Scoop Bucket

A small [Scoop](https://scoop.sh) bucket for installing [Lyricify](https://lyricify.app) from the official [WXRIW/Lyricify-App](https://github.com/WXRIW/Lyricify-App) GitHub releases.

## Usage

```powershell
scoop bucket add lyricify https://github.com/Lyricify/Scoop
scoop install versions/windowsdesktop-runtime-6.0
scoop install spotify
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

Lyricify requires .NET Desktop Runtime 6, which can be installed from Scoop with `scoop install versions/windowsdesktop-runtime-6.0`.

Installing .NET Desktop Runtime 6 requires admin permissions. On Windows 11 25H2 or later with `sudo` enabled, use `sudo scoop install versions/windowsdesktop-runtime-6.0` instead.

_Spotify can also be installed from Scoop :D_ `scoop install spotify`.
