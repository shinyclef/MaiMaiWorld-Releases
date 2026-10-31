# MaiMai World — public downloads

Public test builds only. Game source is maintained separately in a private repository.

## Download v0.2-test

[Release notes and downloads](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/tag/v0.2-test) · [All releases](https://github.com/shinyclef/MaiMaiWorld-Releases/releases)

- [Android APK](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.2-test/MaiMaiWorld-Test-v0.2.apk) — ARM64, intended for the Galaxy S20.
- [Windows ZIP](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.2-test/MaiMaiWorld-Test-v0.2-Windows.zip) — Windows x86-64.

## Install and try

**Android:** Download the APK on your phone and open it. If prompted, allow installation from the browser or file manager you used, then install. You can revoke that source permission afterward. Do not disable Play Protect or other security protections; report any blocking warning.

**Windows:** Download and extract the ZIP, then open `MaiMaiWorld-Test-v0.2.exe`. No Godot editor is required. This build is unsigned; report any blocking publisher or security warning rather than disabling security protections.

Drag the character around the room, release it to increase the movement counter, and tap or click Reset to return it home.

## Test status

This is an early installation/input test, not the full game. No persistent saves or multiplayer; positions reset on a fresh launch. The v0.2 update adds new cartoon character and room artwork. All 28 automated interaction/layout assertions passed, including wide-screen layout checks. Native Linux QA passed at 1280×720 for rendering, mouse drag/release, extreme drag bounds and Reset; native wide-screen QA remains unverified. The updated Android and Windows builds still require device/runtime testing.
