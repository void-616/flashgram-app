# FlashGram

A Telegram file downloader for Android. Downloads media and files from Telegram in the background and saves them directly to your device storage, with support for custom save locations.

> **Closed source app.** This repository hosts builds and releases only.

## Features

- **Material 3 design** with a dynamic accent color picker (Gold, Sapphire, Emerald, Crimson)
- **Simple login**: sign in with just your phone number. FlashGram comes with a built-in API ID, so there is nothing to set up first. If you prefer your own, you can use it from the bottom of the phone-number screen
- **Swipe navigation**: swipe left and right to move between Settings, Downloads and History, or tap the bottom bar
- **Background downloads**: downloads continue via a foreground service with a live progress notification, even while you're using other apps
- **Pause and resume**: pause a download and pick it back up later without losing progress, even after closing and reopening the app
- **Download queue**: queue up multiple downloads; they run one at a time so nothing competes for bandwidth
- **Multiple accounts**: save up to three Telegram accounts and switch between them from Settings → Account. Accounts whose session was ended from another device are removed automatically
- **Custom save location**: choose exactly where your downloads go, whether that's internal storage or an SD card, and override it per download when you need to
- **Storage usage preview**: see how much space a download will actually use, and how much you'll have left, before it starts
- **Download history**: keep track of everything you've downloaded
- **Built-in updates**: check for new versions and install them from inside the app

## Download

Grab the latest APK from the [Releases](https://github.com/void-616/flashgram-app/releases) page.

Most people should download the **universal** APK (works on any Android device). If you know your device's CPU architecture and want a smaller download, per-architecture builds (`arm64-v8a`, `armeabi-v7a`, `x86_64`) are also available on each release. Most modern phones use `arm64-v8a`.

### Installing

Since FlashGram isn't distributed through the Google Play Store, you'll need to allow installs from this source:

1. Download the APK from the Releases page above.
2. Open the downloaded file. Android will ask for permission to install unknown apps if you haven't already granted it for your browser or file manager.
3. Follow the prompts to install.

## Requirements

- Android 10 (API 29) or newer
- A Telegram account
- Optional: your own free Telegram API ID and API Hash from [my.telegram.org/apps](https://my.telegram.org/apps). FlashGram has a built-in one, so you only need this if you want to use your own. The "Use your own Telegram app API credentials" option on the phone-number screen explains the steps

## Updates

FlashGram includes an in-app update checker (Settings → About → Check for updates), which checks this repository's Releases for a newer version. When one is available, the app downloads the build that matches your device and opens Android's installer. Android will ask once for permission to install apps from FlashGram.

Update files are saved to `Download/FlashGram/Updates/` (or the same location as your other downloads, if you picked a custom folder), and you can delete them afterwards.

## Support

Found a bug or have a suggestion? Open an issue on this repository.
