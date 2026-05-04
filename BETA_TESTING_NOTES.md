# SAB Audio — Beta Testing Notes

Thank you for helping test SAB Audio before it ships on the App Store. Your feedback during this phase has the highest possible impact — it directly shapes what v1 looks like to everyone else.

## How to Get the Beta

The beta runs through **TestFlight**, Apple's official beta-testing platform.

1. Install the **TestFlight** app from the App Store on your iPhone or iPad
2. Open the invitation link the developer sent you (in email or via this repo)
3. Tap "Accept" → "Install"
4. SAB Audio appears on your home screen with a dotted "TF" badge until it goes public

If you weren't directly invited but want to help test, email [support@youritsolution.dk](mailto:support@youritsolution.dk) with your Apple ID email and the device(s) you'd like to test on.

## What to Test

### Critical paths (please cover at least these)

- [ ] **First import** — open the app, tap Library → + → Import Folder, pick a folder in iCloud Drive containing audio
- [ ] **Playback** — tap a track, verify audio plays through your iPhone speaker, headphones, and AirPlay
- [ ] **Background playback** — start a track, lock the iPhone, verify audio continues
- [ ] **Lock-screen controls** — verify play/pause/skip work from the lock screen and Control Center
- [ ] **Mini player** — verify it appears at the bottom and tapping it opens Now Playing
- [ ] **Folder browser** — Library tab → Folders filter, drill into nested folders
- [ ] **Multi-select** — tap Select in any list, tick a few tracks, try each Action item
- [ ] **Sleep timer** — set "End of Current Track" → start playback, verify the playback pauses when the track ends
- [ ] **Smart Playlist** — Playlists tab → Smart segment → create one with 2 rules, verify it populates correctly
- [ ] **Resume positions** — play an audiobook (m4b file or any track over 10 minutes), pause partway, leave the app, return — verify it offers to resume

### Stretch goals (please try if you can)

- [ ] **EQ presets** — change presets while playing; verify it applies in real time
- [ ] **Pure Mode** — Settings → Audiophile → enable; verify EQ + crossfade are visibly disabled
- [ ] **Crossfade** — Settings → Playback → enable crossfade, set 6 seconds; play through end of one track to next
- [ ] **iPad split view** — open on iPad, verify the sidebar layout
- [ ] **Listening history** — Settings → Maintenance → Listening History after listening for a while
- [ ] **Pin offline** — pin a track for offline, then enable Airplane Mode and verify it still plays

> **Note:** CarPlay support is **not** in this beta. It's planned for the v1.1 Pro update along with album-artwork auto-fetch. Please don't include CarPlay-related issues in your feedback for this beta.

## What We Need From You

When something doesn't work, please tell us:

> **Device:** iPhone 15 Pro / iOS 17.4
> **What I did:** I tapped X then Y
> **What I expected:** Z should have happened
> **What actually happened:** A
> **Library size (approximate):** 800 tracks / 4,000 tracks / etc.

A two-sentence bug report with that pattern is more useful than a detailed essay. If you can include a screenshot, even better.

## Where to Send Feedback

- **Public** (others might benefit): open a [Discussion](https://github.com/youritsolution/sabaudio/discussions) under the Bugs and Feedback category
- **Private**: email [support@youritsolution.dk](mailto:support@youritsolution.dk) — please reply to the original beta invite email so we can match you to your TestFlight install

## What Beta Means

This is a **release candidate**. The app is feature-complete; we're hunting bugs and verifying behavior on real devices and real iCloud libraries. We're not adding major new features during the beta. If a feature you want is missing, log it as an Idea — we'll consider it for v1.1 or later.

## What Stays Confidential

- Specifics of unannounced features in the app — wait until public release before sharing screenshots
- Pricing (if mentioned in beta materials) — this can change before launch
- The TestFlight invitation link — don't share with people who weren't approved as testers

## Thanks

Beta testing is a real time investment. Thank you for spending it on SAB Audio. The names of testers who provided meaningful feedback during the beta will be acknowledged in the v1 release notes (with permission).

— SAB / Your IT Solution
