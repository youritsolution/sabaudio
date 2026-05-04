# SAB Audio

An iCloud-native hi-fi audio player for **iPhone** and **iPad** that plays the music and audiobooks you already own — referenced in place from iCloud Drive, never duplicated on your device.

## Download

**[View on the App Store](https://apps.apple.com/app/sab-audio/)** — *(link active once the app is approved by Apple Review)*

- iPhone and iPad on iOS 17 or later
- Universal binary (Apple Silicon iPad supported)

## What It Does

- Plays MP3, M4A (AAC + ALAC), FLAC, WAV, AIFF, AAC, M4B audiobooks, and CAF
- **References files in iCloud Drive** — 4,000+ tracks take zero device storage you didn't already have
- **Pure Mode** — bit-perfect playback with every DSP stage bypassed end-to-end
- **Sample-rate matching** — requests the source's native rate from the connected output (USB DACs over Lightning or USB-C)
- **EBU R128 K-weighted loudness analysis** — proper measurement, not a heuristic — with album-mode and track-mode Replay Gain
- **Sample-accurate gapless** on same-album tracks; configurable crossfade up to 30 seconds otherwise
- **Audiobook smarts** — auto-detects long-form content, switches to spoken-word speed (1.25× by default), navigates m4b chapters, fades out at sleep timer end, resumes where you left off
- **10-band parametric EQ** with 12 built-in presets and unlimited custom presets, plus per-output-route memory
- **Smart playlists** with rules over genre, play count, days since played, favorite status, audiobook flag, and more
- **Multi-select bulk actions** — Play Now, Shuffle, Play Next, Add to Queue, Save as Playlist, Save as Session, Favorite All, Pin Offline
- **Folder browsing** mirroring your iCloud Drive structure with recursive selection
- **Library hygiene** — Find Duplicates, Repair Broken Links, Tag Editor with user-edit flag preservation
- **Listening history timeline** with streaks and top artist
- **Continue Listening shelf** for resumable items
- **AirPlay**, lock-screen controls, **Siri Shortcuts**
- **No analytics, no ads, no tracking** — Last.fm and MusicBrainz integrations are off by default

> **Coming in v1.1 (Pro):** CarPlay support, automatic album-artwork lookup via the MusicBrainz Cover Art Archive, and additional power-user features. v1.0 is free and feature-complete on its own; the Pro upgrade will be a one-time in-app purchase.

## A Note on Album Artwork

SAB Audio v1.0 displays the artwork that is **embedded inside each audio file** (the cover image written into the file's metadata tags). Files that were ripped or downloaded without embedded artwork — common with low-bitrate MP3s and many YouTube-sourced tracks — will show a music-note placeholder rather than a cover image.

Automatic online cover-art lookup against the MusicBrainz Cover Art Archive is planned for the **v1.1 Pro update**, alongside CarPlay support. Once Pro is enabled, SAB Audio will be able to fetch and cache covers for tracks whose files do not carry embedded art.

## Privacy First

SAB Audio collects nothing. There are no analytics SDKs, no advertising frameworks, no crash-reporting third parties, and no tracking technologies of any kind.

The two optional network integrations are **off by default**:

- **MusicBrainz** — fetches missing metadata (composer, conductor, performer, album info). Sends only the track title and artist; no personal data
- **Last.fm scrobbling** — sends track title, artist, album, duration, and play timestamp. Authentication uses Last.fm's session-key flow; SAB Audio never sees or stores your Last.fm password

You can disable either at any time in Settings.

## Documentation

- **Product page** — [youritsolution.dk/sabaudio.html](https://youritsolution.dk/sabaudio.html)
- **Privacy policy** — [youritsolution.dk/sabaudio-privacy.html](https://youritsolution.dk/sabaudio-privacy.html)
- **Support** — [youritsolution.dk/sabaudio.html#support](https://youritsolution.dk/sabaudio.html#support)

## Community

Use **[Discussions](https://github.com/youritsolution/sabaudio/discussions)** for:

- Setup questions and troubleshooting
- Feedback, bug reports, and feature requests
- Sharing playlist ideas, smart-playlist rule recipes, and EQ presets
- Audiophile tips — DAC pairings, AutoEQ profiles, room observations
- Audiobook recommendations and listening flow ideas

For private support or sensitive bug reports, email **[support@youritsolution.dk](mailto:support@youritsolution.dk)** instead.

## Suggested Discussion Categories

- **Announcements** — release notes and important updates
- **General** — anything that does not fit the other categories
- **Setup Help** — first-run, iCloud Drive imports, file format support
- **Audiophile** — Pure Mode, USB DACs, sample rates, EQ tuning, headphone profiles
- **Audiobooks** — chapters, sleep timer, resume positions, spoken speed
- **Smart Playlists** — rule recipes and library organization
- **Ideas** — feature requests and workflow suggestions
- **Bugs and Feedback** — issue reports and structured feedback

## Reporting Bugs

When opening a bug report, please include:

- Your iPhone or iPad model (e.g., "iPhone 15 Pro" or "iPad Pro 12.9-inch, 6th gen")
- Your iOS version (Settings → General → About → iOS Version)
- A one-line description of what you did and what you expected
- Steps to reproduce, if you have them
- Screenshots if visual

That's all. We don't need diagnostic dumps or device logs in most cases.

## License & Source Code

The SAB Audio app is closed-source. This repository is a **public community hub** for downloads, documentation, support, and discussions — the app's source code is not distributed here.

## Author

SAB / Your IT Solution — [youritsolution.dk](https://youritsolution.dk)
