# 3D-testing — Mario vs Luigi Android test harness

This repository is a test harness for checking the New Super Mario Bros. DS "Mario vs Luigi" fan-remake on Android.

## Why the upstream source is not vendored here

The upstream remake and mobile ports contain third-party/Nintendo-derived assets and do not expose a clear repository license. Because this repository is public, this repo intentionally does **not** copy the complete upstream source tree.

Instead, the workflow downloads an existing Android build for device testing. For source-level work, use a private repository or work from the upstream repositories directly.

## Reference projects

- Desktop/current remake: https://github.com/ipodtouch0218/NSMB-MarioVsLuigi
- Existing Android port: https://github.com/BasHeemskerk/NSMB-MarioVsLuigi-Android
- Earlier Android port: https://github.com/Wark19/NSMB-Mario-Vs-Luigi-Mobile

## Android smoke-test APK

Run the **Fetch Android test APK** workflow. It downloads the Android port v3.2 APK and publishes it as a GitHub Actions artifact.

This is for compatibility/controls testing only. It is not a build of Jape and it is not the latest desktop remake.
