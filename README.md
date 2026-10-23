# CCTV for Android TV

[Download CCTV 0.3.0 APK](https://raw.githubusercontent.com/pnntrn/cctv-updates/50314946501bd4287398fc339280b6c2e4bd829b/apks/cctv-0.3.0-1006.apk) · 430,842 bytes (421 KiB)

Lightweight RTSP viewing for Android TV and TV sticks. Supports location profiles, 1/4/9/16 substream tiles, fullscreen mainstream, and remote-controlled camera ordering.

## Updates

Install this version once, then use **Settings → Check for updates → Download update → Install** for future releases. Android may ask you to allow installation from CCTV and confirm the update.

Signed releases use the same permanent key to preserve saved cameras. Moving from an older debug build may require a one-time uninstall; signed 0.2 releases can update in place.

This repository holds public APKs and update information only. Application source remains private. No camera credentials, signing keys or account tokens are published.

## Verification

Android build, unit tests, and lint passed locally. APK signature verified against the retained release certificate. GitHub Actions could not start because of an account billing/spending-limit block. The updated native emulator smoke test and real-TV installer flow have not yet completed validation.

APK SHA-256: `a43862eee23d484b36ffe4158f9aa561dd32eaa2dded212032777ff1ec591bb0`

Signing certificate SHA-256: `4bb96b0ff9021cc49885f9cdd02d62ec3e58c3704cd65853e8dc2269316c5f9b`
