# 🎵 SparkieRadio

Sparkie Studio's shared live radio station. Upload MP3s here and **all users hear them automatically** — no config needed.

## How to add songs

1. Upload your `.mp3` file to the `/songs/` folder in this repo
2. Add an entry to `playlist.json` (copy the format below)
3. Sparkie Studio picks it up on the next sync (every 5 minutes) or on manual refresh

## `playlist.json` format

```json
[
  {
    "id": "unique-id-here",
    "title": "Song Title",
    "artist": "Artist Name",
    "url": "https://raw.githubusercontent.com/Draguniteus/SparkieRadio/main/songs/your-file.mp3"
  }
]
```

## Rules
- Files must be `.mp3`, `.ogg`, `.aac`, or `.wav`
- Use the raw GitHub URL format above — NOT the GitHub file page URL
- No DRM-protected audio (it won't play in a browser)
- Keep file sizes reasonable (under 20MB per track for fast loading)

## Raw URL pattern
```
https://raw.githubusercontent.com/Draguniteus/SparkieRadio/main/songs/FILENAME.mp3
```

---
*Powered by Sparkie Studio* ✨
