# World Free TV

A minimal Android TV app that opens https://famelack.com/tv in a full-screen WebView.

## Features

- Full-screen video playback
- Appears on the Android TV home screen
- Remote control friendly: the Back button navigates browser history
- Requires only the Internet permission

## Requirements

- Android TV or Google TV, Android 5.0 (API 21) or newer
- Internet connection

## Build

The APK is built automatically by GitHub Actions on every push. Download `world-free-tv-apk` from the Artifacts section of the workflow run.

To build locally, open the project in Android Studio and choose Build > Build APK(s).

## Install

    adb connect <TV_IP>:5555
    adb install app-debug.apk

Or copy the APK to a USB drive and open it with a file manager on the TV.
