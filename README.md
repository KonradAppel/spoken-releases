# Spoken for macOS

Official downloadable macOS builds and the Sparkle update feed for Spoken.

[Download Spoken 0.2.11 (Build 25)](https://github.com/KonradAppel/spoken-releases/releases/download/v0.2.11-alpha.1-test.25/Spoken-0.2.11-alpha.1-build.25-arm64.dmg)
· [Release notes](https://github.com/KonradAppel/spoken-releases/releases/tag/v0.2.11-alpha.1-test.25)

## Install

1. Open the latest pre-release under
   [Releases](https://github.com/KonradAppel/spoken-releases/releases).
2. Download the `.dmg`.
3. Drag `Spoken.app` into `Applications`.
4. Eject the disk image and open Spoken from Applications.

Current test builds are intended for Apple Silicon Macs with macOS 15 or newer.
Since 0.2.10 they are signed with a Developer ID and notarized by Apple, so
macOS opens them without extra steps. Follow the notes on the individual
release page.

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
