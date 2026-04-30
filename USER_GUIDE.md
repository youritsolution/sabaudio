# SAB Audio User Guide

## Your Premium iOS Audio Player

SAB Audio is a sophisticated audio player for iPhone and iPad that plays your audio files directly from iCloud Drive, Google Drive, Dropbox, or any storage -- no file duplication, no wasted space. It features a dual-deck crossfade engine, 10-band equalizer with custom presets, playlists, playback sessions, bookmarks, A-B repeat loop, bass boost, queue management, sleep timer, AirPlay, listening stats, shake to shuffle, background playback, and lock screen controls.

---

## Getting Started

### First Launch

When you open SAB Audio for the first time, a brief onboarding walkthrough introduces the three pillars of the app:

1. **Your Music, Your Way** -- import from anywhere, zero storage overhead
2. **Studio-Grade Sound** -- 10-band EQ with custom presets
3. **Playlists, Sessions & More** -- full playback management

Tap **Get Started** or **Skip** to enter the app.

### Importing Your Music

**Import Individual Files:**

1. Open SAB Audio and tap the **Library** tab
2. Tap the **+** button in the top-right corner
3. Choose **Import Files**
4. The iOS file picker opens -- navigate to your audio files in **iCloud Drive**, **On My iPhone**, **Google Drive**, **Dropbox**, or any connected storage
5. Select one or multiple files
6. Tap **Open** -- SAB Audio reads the metadata (title, artist, album, artwork) and adds them to your library

**Import an Entire Folder:**

1. Tap the **+** button in the top-right corner
2. Choose **Import Folder**
3. Select any folder -- SAB Audio will recursively scan it and import all audio files found inside, including subfolders
4. A progress indicator shows the scanning status

**No files are copied.** SAB Audio creates a reference to each file's original location, so your music does not take up double the space on your device.

---

## Playing Music

### Starting Playback

- Tap any track in the Library, Search results, or a Playlist to start playing
- The **Mini Player** appears at the bottom of the screen showing the current track
- Tap the Mini Player to open the full **Now Playing** screen

### Now Playing Screen

The Now Playing screen is your main control center:

- **Album Artwork** -- displayed large with a blurred background gradient; scales subtly when paused
- **Track Info** -- title below the artwork, with tappable artist and album links:
  - Tap **artist name** to see all tracks by that artist
  - Tap **album name** to see all tracks in that album
  - Tap **folder chip** to see the folder the track came from
- **Queue Source** -- a chip at the top shows where the current queue came from
- **Content Type Chip** -- shows whether the track is detected as Music or Spoken Audio, with a menu to override
- **Bookmarks Chip** -- shows bookmark count; tap to view and manage saved positions
- **Resume Chip** -- appears when a track has a saved resume position; tap to jump back
- **Progress Scrubber** -- a thin line with a draggable playhead; touch and drag to seek to any position. The playhead enlarges when you touch it for precise control
- **Time Display** -- current time on the left, remaining time on the right
- **Playback Controls** (center row):
  - **Shuffle** (left) -- tap to randomize the queue order
  - **Skip Back** -- jump backward (configurable: 5-60 sec for music, 10-90 sec for spoken audio)
  - **Play/Pause** -- large center button
  - **Skip Forward** -- jump forward (configurable interval)
  - **Repeat** (right) -- cycles through: Off, Repeat All, Repeat One
- **Volume Slider** -- drag left/right to adjust volume

**Feature Grid** (bottom):

| Button | Function |
|--------|----------|
| Queue | View and manage the current queue |
| EQ | Open the 10-band equalizer |
| Speed | Change playback speed (0.25x to 3.0x) |
| Sleep | Set a sleep timer |
| Previous | Go to previous track |
| Next | Go to next track |
| AirPlay | Choose audio output device |
| Playlist | Add the currently playing track to a playlist |
| Bass Boost | One-tap bass enhancement on/off |
| A-B Loop | Set a loop section within the track |

### Mini Player

The Mini Player floats above the tab bar whenever a track is loaded:

- Shows artwork thumbnail, track title, and artist
- **Play/Pause** and **Next** buttons for quick control
- A thin progress line at the top shows playback position
- Tap anywhere on it to open the full Now Playing screen

### Background Playback & Lock Screen

SAB Audio continues playing when you lock your device or switch to another app. Control playback from:

- **Lock Screen** -- play/pause, next, previous, and seek
- **Control Center** -- swipe down from the top-right corner
- **Headphone Controls** -- play/pause, skip via your headphone buttons

### AirPlay

Tap the **AirPlay** button in the Now Playing feature grid to choose your audio output: iPhone speaker, AirPods, HomePod, Bluetooth speaker, Apple TV, or any AirPlay-compatible device.

### Crossfade

SAB Audio uses a dual-deck audio engine that can seamlessly crossfade between tracks. Enable crossfade in **Settings > Playback > Crossfade**, then adjust **Blend Duration** from 1 to 30 seconds. When the current track nears its end, the next track in the queue begins playing and the volumes fade smoothly.

---

## Content Type Detection

SAB Audio automatically detects whether a track is **Music** or **Spoken Audio** (audiobooks, podcasts, lectures):

- **.m4b files** are always detected as Spoken Audio
- **Tracks longer than the Long-Form Threshold** (configurable in Settings) are detected as Spoken Audio
- **All other tracks** default to Music

When a track is detected as Spoken Audio:
- Skip intervals change (e.g., 30 seconds instead of 15)
- Resume position is automatically saved
- Playback speed can auto-switch to your preferred spoken speed

### Overriding Detection

Tap the **content type chip** in Now Playing to manually override for any track:
- **Automatic** -- let the app detect
- **Music** -- force music behavior
- **Spoken Audio** -- force spoken audio behavior

---

## A-B Repeat Loop

Loop any section of a track -- perfect for musicians learning riffs, language learners, or students reviewing lectures.

1. Tap the **A-B Loop** tile in the Now Playing feature grid
2. **First tap** sets point A (start of loop) -- the tile shows "A: 1:23"
3. **Second tap** sets point B (end of loop) -- the tile shows "1:23 -> 2:45" and looping begins
4. The track automatically seeks back to point A each time it reaches point B
5. **Third tap** clears the loop

---

## Bass Boost

One-tap bass enhancement without opening the full equalizer:

- Tap the **Bass Boost** tile in the Now Playing feature grid
- **On**: Applies +8/+6/+4/+2 dB boost to the 32Hz, 64Hz, 125Hz, and 250Hz bands
- **Off**: Restores your previous EQ settings
- The tile glows warm orange when active

---

## Library Management

### Browsing Your Library

The Library tab offers five segments:

| Segment | Shows |
|---------|-------|
| **All** | Every imported track |
| **Favorites** | Tracks you have marked as favorites |
| **Artists** | Browse grouped by artist |
| **Albums** | Browse grouped by album |
| **Folders** | Browse by original folder structure |

### Folder Browsing

The **Folders** tab builds a navigable tree from the original folder structure of your imported files. If you organized your music into folders on iCloud Drive or your device, SAB Audio preserves that organization:

- Navigate into folders and subfolders
- See track count and subfolder count for each folder
- **Play All** -- plays every track in the folder and all subfolders
- **Shuffle** -- plays all tracks in the folder in random order
- Tap any track to play it with the folder contents as the queue

This is especially useful for users who organize music by genre, mood, event, or project using folders.

### Navigate from Now Playing

While a track is playing, you can navigate directly to related content:

- **Tap the artist name** (blue link) -- opens a sheet showing all tracks by that artist with Play All and Shuffle buttons
- **Tap the album name** -- opens a sheet showing all tracks in that album with artwork, Play All, and Shuffle
- **Tap the folder chip** (appears below the album) -- opens the folder the track lives in, showing sibling tracks and subfolders

### Sorting

Tap the **sort icon** (top-left) to choose a sort order:

- Date Added
- Title
- Artist
- Album
- Duration

Tap the same option again to toggle ascending/descending.

### Duplicate Detection

SAB Audio automatically scans for duplicates after every import. If duplicates are found, an alert offers to review them.

**Finding duplicates:**
- After import: automatic alert with duplicate count
- Anytime: Library **+** menu → **Find Duplicates**

**Managing duplicates:**
- Each duplicate group shows all copies with the earliest import marked "KEEP"
- Remove individual duplicates with the red trash button
- **Remove All** removes every duplicate at once, keeping the earliest version
- Duplicates are matched by title + artist (case-insensitive)

### Track Actions

**Swipe left** on a track to reveal:
- **Queue** -- add to the end of the current queue
- **Delete** -- remove from library

**Swipe right** on a track to reveal:
- **Favorite** -- toggle favorite status
- **Add to Playlist** -- choose or create a playlist

**Long-press** (context menu) on a track:
- **Play Next** -- insert right after the current track
- **Play Later** -- add after the "play next" block
- **Add to End of Queue** -- append to the queue

---

## Playlists

### Creating a Playlist

1. Go to the **Playlists** tab (select the "Playlists" segment)
2. Tap the **+** button
3. Type a name and tap **Add** or press Return

### Managing Playlists

- **Play All** -- plays the entire playlist in order
- **Shuffle** -- plays the playlist in random order
- **Add Tracks** -- tap **+** in the playlist detail view to browse and add tracks
- **Remove Tracks** -- swipe left on a track and tap Remove
- **Reorder Tracks** -- tap Edit and drag tracks to a new position
- **Delete Playlist** -- tap Edit in the Playlists list and delete

---

## Playback Sessions

Sessions save your entire playback state -- queue, position, EQ settings, playback rate, repeat mode, and shuffle state -- so you can return to exactly where you left off.

### Saving a Session

1. Open the **Queue** view from Now Playing
2. Tap the **...** menu (top-right)
3. Choose **Save Queue as Session**
4. Enter a name and tap Save

### Loading a Session

1. Go to the **Playlists** tab and select the **Sessions** segment
2. Tap any session to restore it
3. All your queue, position, and settings are restored

### Session Actions (long-press)

- **Load Session** -- restore the saved state
- **Overwrite with Current** -- update the session with your current state
- **Duplicate** -- create a copy
- **Rename** -- change the session name
- **Delete** -- remove the session

---

## Bookmarks

Create named bookmarks at specific positions within a track -- perfect for audiobooks, lectures, or long mixes.

### Creating a Bookmark

1. In the Now Playing screen, tap the **Bookmarks** chip below the track info
2. Tap the **+** button in the top-left corner
3. Enter a name for the bookmark
4. Tap **Save** -- the current playback position is saved

### Using Bookmarks

- Tap any bookmark to jump to that position
- Swipe left on a bookmark to delete it
- Bookmarks persist across app restarts
- A **Resume** chip appears in Now Playing when the track has a saved resume position

---

## Equalizer

Access the Equalizer from the **EQ** button in the Now Playing feature grid, or from **Settings > Playback > Equalizer**.

### 10-Band Parametric EQ

| Band | Frequency |
|------|-----------|
| 1 | 32 Hz |
| 2 | 64 Hz |
| 3 | 125 Hz |
| 4 | 250 Hz |
| 5 | 500 Hz |
| 6 | 1 kHz |
| 7 | 2 kHz |
| 8 | 4 kHz |
| 9 | 8 kHz |
| 10 | 16 kHz |

Each band can be adjusted from **-12 dB** to **+12 dB** in 0.5 dB steps. Drag the circular thumb on each band slider up or down. You will feel a subtle haptic tick as you adjust.

### Built-in Presets (12)

Flat, Rock, Pop, Jazz, Classical, Bass Boost, Treble Boost, Vocal, Electronic, Hip-Hop, Acoustic, Late Night

### Custom Presets

1. Adjust the EQ bands to your preference
2. Tap **Save Current as Preset**
3. Enter a name and tap **Save**

Your custom presets appear in the **MY PRESETS** section. Long-press a custom preset to delete it. Custom presets are saved permanently.

### EQ Toggle

Use the toggle switch at the top to enable or disable the entire equalizer without losing your settings.

---

## Queue Management

Access the Queue from the **Queue** button in the Now Playing feature grid, or the queue icon in the top-right of the Now Playing screen.

- **Queue Source** -- shows where the queue originated (Library, Playlist, Search, Session)
- **Now Playing** -- the currently playing track is highlighted at the top
- **Up Next** -- all remaining tracks in the queue
- Tap any track in Up Next to jump to it
- Swipe left to remove a track from the queue
- Tap **Edit** to reorder tracks by dragging
- **Clear Upcoming** -- remove all upcoming tracks from the queue

### Save Queue

Tap the **...** menu to:
- **Save Queue as Playlist** -- create a new playlist from the current queue
- **Save Queue as Session** -- save the full playback state for later

---

## Search

The **Search** tab helps you find tracks and folders quickly:

- Type in the search bar to filter by **title**, **artist**, **album**, **genre**, or **folder name**
- Results update in real time as you type
- **Folder results** appear at the top -- tap to navigate into the matching folder
- **Track results** appear below -- tap any result to play it
- Long-press for context menu: Play Next, Play Later, Add to End of Queue

When not searching, the Search tab shows:

- **Continue Listening** -- tracks with resume positions
- **Recently Added** -- your latest imports
- **Recently Played** -- your last 10 played tracks
- **Most Played** -- your top 10 most-listened tracks

---

## Playback Speed

Access speed controls from the **Speed** button in the Now Playing feature grid.

| Speed | Use Case |
|-------|----------|
| 0.25x | Ultra-slow for detailed analysis |
| 0.5x | Slow playback |
| 0.75x | Slightly slowed |
| 1.0x | Normal speed |
| 1.25x | Slightly faster |
| 1.5x | Fast playback |
| 1.75x | Very fast |
| 2.0x | Double speed |
| 2.5x | Audiobook power listener |
| 3.0x | Maximum speed |

The original pitch is preserved at all speeds -- voices will not sound distorted.

SAB Audio can automatically switch to a different playback speed for spoken audio content. Configure this in **Settings > Long-Form Audio > Use Spoken Speed**.

---

## Sleep Timer

Access the Sleep Timer from the **Sleep** button in the Now Playing feature grid.

### Preset Timers

Tap any preset to start a countdown: **5, 10, 15, 20, 30, 45, 60, 90,** or **120 minutes**.

### Custom Timer

1. Tap **Set Custom Time**
2. Use the hour (0-12) and minute (0-59) wheel pickers
3. Tap the **Start** button

### Active Timer

When a timer is running:

- A circular progress indicator shows time remaining
- The remaining time displays in the Now Playing feature grid
- Tap **Cancel Timer** to stop it early
- When the timer reaches zero, playback pauses automatically

---

## Listening Stats

SAB Audio tracks your listening time automatically:

- **Today** -- hours and minutes listened today
- **All Time** -- total accumulated listening across all sessions

View your stats in **Settings > Listening**.

---

## Shake to Shuffle

Shake your iPhone while music is playing to shuffle the queue. If the queue is already shuffled, shaking re-shuffles to a new random order.

Toggle this feature on/off in **Settings > Listening > Shake to Shuffle**.

---

## Settings

The **Settings** tab provides:

### Playback

- Playback speed (0.25x - 3.0x)
- Volume level
- EQ preset (tap to open equalizer)
- Crossfade toggle and blend duration (1-30 seconds)

### Listening

- Today's listening time
- All-time listening total
- Shake to Shuffle toggle

### Long-Form Audio

- Remember Position toggle
- Long-Form Threshold (3-60 minutes)
- Default Skip interval (5-60 seconds)
- Spoken Skip interval (10-90 seconds)
- Use Spoken Speed toggle and speed picker (1.0x - 3.0x)

### Queue

- Restore Queue on Launch toggle
- Current Queue count

### Library

- Total number of tracks
- Total library duration
- Number of favorite tracks
- Import More Files / Import Folder buttons

### File Links

- Available / Needs Download / Needs Repair counts
- Refresh Library Links button

### Storage

- File mode (References -- no copies)
- Remove All from Library

### About

- App version
- Developer: SAB
- Support email: support@youritsolution.dk
- Privacy Policy link
- Terms of Use link

---

## Accessibility

SAB Audio supports VoiceOver and assistive technologies:

- All playback controls have descriptive labels and hints
- The playback scrubber and volume control support VoiceOver adjustable actions
- Track rows announce title, artist, duration, and playing state
- EQ band sliders support VoiceOver adjustable actions (swipe up/down to change gain)
- Mini player controls are fully labeled
- Haptic feedback accompanies all key actions for tactile confirmation

---

## Haptic Feedback

SAB Audio provides tactile feedback throughout:

- **Medium tap** -- play/pause, next track, previous track, bass boost toggle, A-B loop toggle
- **Light tap** -- skip forward/backward, shuffle, repeat, EQ toggle, dismiss
- **Selection tick** -- EQ band adjustment, preset selection, speed change, content type change
- **Success** -- import completed, custom preset saved, bookmark saved, session saved

---

## Supported File Formats

| Format | Extension |
|--------|-----------|
| MPEG-4 Audio | .m4a |
| MPEG-4 Audiobook | .m4b |
| AAC | .aac |
| MP3 | .mp3 |
| FLAC | .flac |
| WAV | .wav |
| AIFF | .aiff, .aif |
| AIFC | .aifc |
| Core Audio Format | .caf |

SAB Audio supports any audio format recognized by Apple's AVFoundation framework.

---

## Troubleshooting

### Track will not play
- Check the file availability status in the Library
- If the file is in iCloud Drive, make sure it is downloaded (not just in the cloud)
- Go to Settings > File Links > Refresh Library Links to re-validate
- Try removing and re-importing the track

### No sound
- Check that the device is not in Silent Mode
- Verify the in-app volume slider is not at zero
- Tap the AirPlay button to confirm the correct output device is selected
- Check that another app is not controlling audio output

### EQ has no effect
- Ensure the EQ toggle is turned on (top of Equalizer screen)
- Check that bands are not all set to 0 dB (Flat)
- If Bass Boost is on, it overrides your EQ until you turn it off

### Import not working
- Ensure iCloud files are downloaded, not just cloud placeholders
- Try using **Import Folder** to select the parent folder
- If scanning gets stuck, files that take too long to read will be added with the filename as title

---

## Coming in Future Updates

- **CarPlay** -- control SAB Audio from your car display
- **Widgets** -- Now Playing widget for lock screen and home screen
- **Chapter Support** -- navigate chapters in .m4b audiobook files

---

*SAB Audio v1.0.0 -- Developed by SAB*
*youritsolution.dk*
