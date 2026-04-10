# SUBT·LAB

A fast, single-file browser-based transcription and subtitling studio.

## Features

* **Universal Input:** Load YouTube videos via URL, pull existing YouTube captions, or upload local video, audio, and subtitle files (`.srt`, `.vtt`, `.txt`).
* **Dual-Track Editing:** Input fields for both original transcription and translation within the same segment block.
* **Speaker Management:** Create, color-code, and assign speakers to specific segments.
* **Productivity Focused:** Built-in keyboard shortcuts for playback, seeking, and segment creation without leaving the text fields.
* **Subtitle Guidelines:** Visual warnings when text exceeds standard subtitle limits (≤42 characters per line, ≤2 lines per segment).
* **Segment Tools:** Easily split, merge, or delete timecoded segments. Auto-scrolls to the active segment during playback.
* **Auto-Save:** Progress is automatically saved to your browser's local storage.
* **Export Options:** Export your work as SRT, WebVTT, or Plain Text (supports exporting transcription, translation, or both).

## Getting Started

Because SUBT·LAB is a completely standalone HTML file, there is no installation or build process required.

1. Download `subt-lab.html`.
2. Double-click the file to open it in any modern web browser.
3. Paste a YouTube URL or click to upload a local media/subtitle file to begin.

## Keyboard Shortcuts

**Global (No text field focused):**
* `Space`: Play / Pause
* `←` / `→`: Seek ±5 seconds
* `↑` / `↓`: Navigate segments
* `N`: Create a new segment at the current playhead
* `Alt + 1–4`: Assign speaker to the active segment
* `[` / `]`: Decrease / Increase playback speed
* `?`: Toggle shortcuts menu

**Inside a text field:**
* `Ctrl + Enter`: Play / Pause
* `Ctrl + Shift + ←`: Seek back 5 seconds
* `Ctrl + Shift + →`: Seek forward 5 seconds
* `Escape`: Blur field (remove focus)

## License

This project is released under [The Unlicense](https://unlicense.org/). It is free and unencumbered software released into the public domain.
