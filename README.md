# FlashGram

A Telegram file downloader for Android. Downloads media and files from Telegram in the background and saves them directly to your device storage, with support for custom save locations.

> **Closed source app.** This repository hosts builds and releases only.

## Features

- **Material 3 design** with a dynamic accent color picker (Gold, Sapphire, Emerald, Crimson)
- **Background downloads** — downloads continue via a foreground service with a live progress notification, even while you're using other apps
- **Pause and resume** — pause a download and pick it back up later without losing progress
- **Download queue** — queue up multiple downloads; they run one at a time so nothing competes for bandwidth
- **Custom save location** — choose exactly where your downloads go, whether that's internal storage or an SD card, and override it per download when you need to
- **Storage usage preview** — see how much space a download will actually use, and how much you'll have left, before it starts
- **Download history** — keep track of everything you've downloaded

## Download

Grab the latest APK from the [Releases](https://github.com/void-616/flashgram-app/releases) page.

Most people should download the **universal** APK (works on any Android device). If you know your device's CPU architecture and want a smaller download, per-architecture builds (`arm64-v8a`, `armeabi-v7a`, `x86_64`, `x86`) are also available on each release.

### Installing

Since FlashGram isn't distributed through the Google Play Store, you'll need to allow installs from this source:

1. Download the APK from the Releases page above.
2. Open the downloaded file. Android will ask for permission to install unknown apps if you haven't already granted it for your browser or file manager.
3. Follow the prompts to install.

## Requirements

- Android 10 (API 29) or newer

## Updates

FlashGram includes an in-app update checker (Settings → About → Check for updates), which checks this repository's Releases for a newer version. Updates aren't installed automatically — you'll need to download and install the new APK yourself for now.

## Support

Found a bug or have a suggestion? Open an issue on this repository.
