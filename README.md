# Spoken for macOS

Official downloadable macOS builds and the Sparkle update feed for Spoken.

[Download Spoken 0.2.9 (Build 23)](https://github.com/KonradAppel/spoken-releases/releases/download/v0.2.9-alpha.1-test.23/Spoken-0.2.9-alpha.1-build.23-arm64-UNSIGNED.dmg)
· [Release notes](https://github.com/KonradAppel/spoken-releases/releases/tag/v0.2.9-alpha.1-test.23)

## Install

1. Open the latest pre-release under
   [Releases](https://github.com/KonradAppel/spoken-releases/releases).
2. Download the `.dmg`.
3. Drag `Spoken.app` into `Applications`.
4. Eject the disk image and open Spoken from Applications.

Current test builds are intended for Apple Silicon Macs with macOS 15 or newer
and are not notarized. If macOS blocks the first launch, open **System
Settings → Privacy & Security** and choose **Open Anyway**. Follow the notes on
the individual release page.

## Updates

Library-based builds 9 and newer use the public `appcast.xml` in this repository. In
Spoken, choose **Spoken → Check for Updates…**. Downloaded updates are
authenticated with Sparkle's EdDSA signature before installation.

This repository contains release assets only. Application development happens
in the separate source repository.

## Support

If Spoken is useful to you, you can
[buy Konrad a coffee](https://buymeacoffee.com/KonradAppel) to support its
independent development.
