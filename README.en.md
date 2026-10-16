<div align="center">

<img src="assets/icon.png" width="112" alt="Drova for Mac">

# Drova for Mac

**Cloud gaming in a native macOS app.**

macOS 14+ · Apple Silicon + Intel · Universal

### [Download DMG](https://github.com/HooMDooM/DrovaMac/releases/latest/download/Drova-macOS-universal.dmg) · [Download ZIP](https://github.com/HooMDooM/DrovaMac/releases/latest/download/Drova-macOS-universal.zip)

[Русский](README.md) · [Releases](https://github.com/HooMDooM/DrovaMac/releases) · [Report an issue](https://github.com/HooMDooM/DrovaMac/issues/new/choose)

</div>

![Game library](assets/screenshots/catalog.png)

An unofficial native macOS client for [Drova](https://drova.io). Browse games and stations, choose a city, adjust streaming quality and play in a window or fullscreen. Windows, Wine and CrossOver are not required.

This repository distributes **compiled applications, screenshots and documentation only**. Application source code is not published.

## Install

1. Download and open the DMG.
2. Drag **Drova.app** to **Applications**.
3. Launch Drova and sign in to your Drova account.
4. Select a game and an available station.

Version 1.0.0 is ad-hoc signed, without Apple Developer ID or notarization. After the first launch attempt, macOS may require **System Settings → Privacy & Security → Open Anyway**. Approve only if you trust the download. [Apple's instructions](https://support.apple.com/en-us/102445).

Choose the **Drova DMG or ZIP**, not GitHub's automatic **Source code** archives, which contain this repository's documentation.

## Features

- Searchable game catalog, city filters and station selection.
- 720p, 1080p and 4K; H.264, HEVC and hardware-supported AV1.
- Server FPS, 10–70 Mbps bitrate limits, compression quality and frame pacing.
- Keyboard, mouse, compatible macOS gamepads and fullscreen.
- Audio buffering, stream statistics and session reconnection.

Actual capabilities depend on the Mac, station and connection. Full Windows feature parity is not claimed: UDP green/yellow, microphone forwarding and external broadcasting are not in this release's supported feature list.

![Stations](assets/screenshots/servers.png)

![Streaming settings](assets/screenshots/settings.png)

Account details are hidden in screenshots. Catalog and station availability change over time. The application interface is currently in Russian.

## Requirements

macOS 14 or later, Apple Silicon or Intel, a Drova account, available service time and an internet connection. AV1 requires hardware support.

App launch was checked on Apple Silicon. Intel was compiled but has not been tested on a physical Intel Mac. A complete streaming session was not part of this release preparation.

## Shortcuts

| Shortcut | Action |
|---|---|
| Esc twice | Release mouse capture |
| ⌘ , | Stream settings |
| ⌘ F | Fullscreen |
| ⌘ I | Statistics |
| ⌘ M | Mute / unmute |
| ⌘ K | Remote on-screen keyboard |
| ⌘ W | End / disconnect dialog |

**Disconnect keeps the remote session active.** Choose **Завершить / End** to end it. Pricing and time accounting are controlled by Drova.

## Updates

End the session, quit the app and replace Drova.app with a new release. Automatic updates are not implemented. Each release includes **SHA256SUMS.txt**.

[Local data](PRIVACY.md) · [Changelog](CHANGELOG.md) · [Issues](https://github.com/HooMDooM/DrovaMac/issues)

Independent unofficial project. Drova, game names and artwork belong to their respective owners. Gaming time and game licenses are not included.
