# Blue Musix - Music Repository

This repository contains processed music files for the Blue Musix application.

## Structure

```
music/
├── hires/     # Hi-Res FLAC files (24-bit/96kHz+)
├── cd/        # CD Quality FLAC files (16-bit/44.1kHz) 
└── mp3/       # MP3 files (320kbps)

album_art/     # Optimized album artwork (800x800 JPEG)
metadata/      # JSON metadata for each song
```

## Quality Processing Rules

- **Hi-Res sources**: Keep original + generate CD Quality + MP3
- **CD Quality sources**: Keep original + generate MP3 (no upsampling)
- **MP3 sources**: Keep as-is (no conversions)

## Last Updated

2025-06-10 12:28:06

Total processed files: 5
