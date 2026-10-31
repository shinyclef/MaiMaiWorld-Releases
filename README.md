# MaiMai World — public downloads

Public test builds only. Game source is maintained separately in a private repository.

## Download v0.5-test

[Release notes and downloads](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/tag/v0.5-test) · [All releases](https://github.com/shinyclef/MaiMaiWorld-Releases/releases)

- [Android APK](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.5-test/MaiMaiWorld-Test-v0.5.apk) — ARM64, intended for the Galaxy S20.
- [Windows ZIP](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.5-test/MaiMaiWorld-Test-v0.5-Windows.zip) — Windows x86-64.

## Install and try

**Android:** Download the APK on your phone and open it. If prompted, allow installation from the browser or file manager you used, then install. You can revoke that source permission afterward. Do not disable Play Protect or other security protections; report any blocking warning.

**Windows:** Download and extract the ZIP, then open `MaiMaiWorld-Test-v0.5.exe`. No Godot editor is required. This build is unsigned; report any blocking publisher or security warning rather than disabling security protections.

## What’s new

**v0.5:** a larger circular app icon, a bigger 132×132 bin target, wall items that can be dragged into the bin without allowing settled floor placement, and a Bedroom collection with a bed, bedside table, portable lamp and alarm clock. The Android touch-dispatch fix from v0.4.1 is retained.

Room editing with movable furniture, rotation, resizable carpets, wall decorations and architecture; two additional family characters; six seamless painted wall/floor finishes; and the approved painted Set A interface icons. The panoramic room retains the painted picture-book style.

Drag characters, props or furniture to arrange the room. Drag empty background horizontally to pan. Use the room-editing controls to add/remove items, change finishes and adjust supported objects. Reset restores the initial arrangement.

## Test status

**Progress is not saved.** This is an early test, not the full game; arrangements reset on a fresh launch, and there is no multiplayer. Older builds remain available under All releases.

The update passed 113 backlog regression assertions, 91 authentic viewport touch-input checks and native Linux desktop checks for the new bin/wall-item behavior and Bedroom spawning, carrying, recoloring and bed support. Automated checks passed: 340 furniture/model, 201 interaction, 34 UI, 10 actual-catalog, 21 finish-provider, 55 UI-icon and 216 Python finish assertions, plus the orientation check. Native Linux QA verified family spawn/delete/re-add, grounded furniture, complete window/painting/flag silhouettes, wall-only placement without baked duplicates, and the new icon interface.

Actual v0.5 Windows and Android runtime/device testing remains pending. Native Ctrl-wheel and pinch input were not exercised; synthetic multi-touch tests passed. Real Android touch, physical device rotation and performance remain unverified.
