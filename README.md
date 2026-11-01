# MaiMai World — public downloads

Public test builds only. Game source is maintained separately in a private repository.

## Download v0.7-test

[Release notes and downloads](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/tag/v0.7-test) · [All releases](https://github.com/shinyclef/MaiMaiWorld-Releases/releases)

- [Android APK](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.7-test/MaiMaiWorld-Test-v0.7.apk) — ARM64, intended for the Galaxy S20.
- [Windows ZIP](https://github.com/shinyclef/MaiMaiWorld-Releases/releases/download/v0.7-test/MaiMaiWorld-Test-v0.7-Windows.zip) — Windows x86-64.

## Important Android upgrade notice

**v0.7 uses a replacement signing certificate. Uninstall the older app before installing this APK. Uninstalling deletes that app’s local data, including any saved profiles.** This is not an in-place upgrade from earlier signed builds.

Download and open the APK. If prompted, allow installation from the browser/file manager you used; revoke that permission afterward if desired. Do not disable Play Protect or other security protections; report blocking warnings.

**Windows:** Extract the ZIP and open `MaiMaiWorld-Test-v0.7.exe`. No Godot editor is required. The build is unsigned; report blocking security warnings instead of disabling protection.

## What’s new

- Approved seaside town map with panning and family-home navigation.
- More natural furniture placement, invalid-drop recovery and destination previews.
- Improved support layering, contact shadows, grounded walking and painted window views.
- Full modular character studio: four ages, 22 categories, 190 catalog tiles, animated previews, custom-character inventory and saved-profile editing, duplication and recoverable Trash.
- Earlier animation, seating, interactive lights, room editing and Bedroom items remain available.

## Saves and test status

**Creator profiles persist; room layouts do not.** Room arrangements reset on a fresh launch. This remains an early test, with no multiplayer. Older builds are available under All releases.

Final source passed 46 Godot suites and 216 Python checks, plus sampled native Linux visual/input QA. Published downloads matched the verified build checksums. Actual Android/Windows hardware performance, mobile text input and every possible creator combination still need device testing. The creator uses shared artwork textures and can have a noticeable memory footprint.
