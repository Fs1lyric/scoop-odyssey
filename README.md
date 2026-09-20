# scoop-odyssey

A [Scoop](https://scoop.sh) bucket for [Odyssey Design](https://github.com/Fs1lyric/odyssey-design).

```powershell
scoop bucket add odyssey https://github.com/Fs1lyric/scoop-odyssey
scoop install odyssey-design
```

This installs the portable Windows build. The video editor shells out to
ffmpeg, so install that too if you want it:

```powershell
scoop install ffmpeg
```

The manifest is generated from the release by `packaging/sync-release.sh` in
the main repository. Edit it there, not here.

Nothing is code-signed, so Windows will warn about an unidentified developer.
The SHA-256 in the manifest is checked on install.
