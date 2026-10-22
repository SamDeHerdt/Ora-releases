# Ora — releases

Downloads and update feed for **Ora**, a light, keyboard-first browser that puts idle tabs to sleep, for macOS, Windows and Linux.

This repository holds **no source code**, only the built app. Ora's source is in a private repository; this public one exists so people can download Ora and installed copies can update themselves, which they can't do from a private repo.

## Install

Get the newest build from [Releases](../../releases/latest):

- **Mac** (Apple silicon): `Ora-<version>-mac.zip`. Unzip, drag Ora to Applications, and the first time open it with right-click → Open (it isn't notarized by Apple). If macOS says it can't be verified, use System Settings → Privacy & Security → Open Anyway.
- **Windows** 10 or 11: `Ora-<version>-windows.zip`. Unzip and run `Ora.exe`. SmartScreen may warn the first time: More info → Run anyway.
- **Linux** (x86-64): `Ora-<version>-linux.tar.gz`. Needs WebKitGTK 4.1 (`sudo apt install libwebkit2gtk-4.1-0` on Debian/Ubuntu). Unpack, and run `./ora`; `ora.desktop` adds it to your app menu.

## Updates

Ora looks here by itself and says when a new version is ready. **Settings → General → Update** downloads it, checks that it was signed with Ora's update key (each file has a matching `.sig`), puts it in place and reopens Ora with your tabs.

© Sam De Herdt. All rights reserved.
