# MaiMai World — public downloads

Public test builds only. Game source is maintained separately in a private repository.

## Download v0.3-test

[Release notes and downloads](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/tag/v0.3-test) · [All releases](https://github.com/shinyclef/MaiMaiWorld-Releases/releases)

- [Android APK](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.3-test/MaiMaiWorld-Test-v0.3.apk) — ARM64, intended for the Galaxy S20.
- [Windows ZIP](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.3-test/MaiMaiWorld-Test-v0.3-Windows.zip) — Windows x86-64.

## Install and try

**Android:** Download the APK on your phone and open it. If prompted, allow installation from the browser or file manager you used, then install. You can revoke that source permission afterward. Do not disable Play Protect or other security protections; report any blocking warning.

**Windows:** Download and extract the ZIP, then open `MaiMaiWorld-Test-v0.3.exe`. No Godot editor is required. This build is unsigned; report any blocking publisher or security warning rather than disabling security protections.

## What’s new

Painted picture-book artwork and a new app icon, a panoramic room, six movable props, freer dragging, simple character animation, and falling/settling motion on release. The selection outline is gone.

Drag the character or a prop; drag empty background horizontally to pan, or hold a dragged object near a screen edge to scroll. Release above supported furniture to land on it, or drop to the floor. Tap or click Reset to restore all objects and the camera.

## Test status

This is an early test, not the full game. No persistent saves or multiplayer; positions reset on a fresh launch. Older builds remain available under All releases.

All 126 automated interaction/art-layout assertions passed. Native Linux QA at 1280×720 verified the painted scene and clean sprite transparency, character/ball/bunny dragging, cup tabletop landing, panning in both directions with a fixed HUD, and Reset. Transient landing timing and idle animation were not fully resolved visually; native wide-screen QA remains unverified. Actual Windows and Android runtime/device testing of v0.3 is still pending.
