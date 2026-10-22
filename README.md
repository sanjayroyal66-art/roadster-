# Roadster Dash Offline — Java Android Canvas remake

This is a playable, offline, native Android 2D endless-road remake built with Java Canvas. It uses original code-drawn graphics and no external game assets, network permissions, or web requests.

## Gameplay in this starter
- Tap to start / restart
- Three lanes; tap the left or right half of the screen (or bottom arrow areas) to change lanes
- Avoid traffic cars
- Collect coins for score
- Collect green fuel cans to restore fuel
- Speed and spawn rate increase as score rises
- Crash or empty fuel ends the run

## Important about the referenced website
The provided `roadsterdash.com` page could not be inspected by the available browser reader, so this project is a clean playable remake, not a verified exact port. It does not use original site source code, branding assets, or copied game files.

## Build APK using only your Android phone
Recommended: GitHub Actions builds it in the cloud, so you do not need a PC.

1. Download and extract this ZIP on your phone.
2. Create a repository on GitHub.
3. Upload all project files, including `.github/workflows/build-apk.yml`.
4. Open the repository's **Actions** tab and enable workflows if asked.
5. Run **Build offline APK** (or push to `main`).
6. Open the successful workflow run and download the `RoadsterDashOffline-debug-apk` artifact.
7. Extract the artifact ZIP and tap `app-debug.apk` to install. If Android asks, allow your file manager/browser to install unknown apps.

## Local build
Requires JDK 17, Android SDK platform 35 and Gradle 8.9:
`gradle assembleDebug`
APK output: `app/build/outputs/apk/debug/app-debug.apk`

This is a debug APK for personal testing. It is not a signed Play Store release.
