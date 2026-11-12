# Boox Settings Shortcut

A minimalist Android shortcut app that opens standard Android System Settings directly from the Onyx Boox app drawer.

## Build with Docker

```bash
docker run --rm -v "$PWD":/project -w /project ghcr.io/cirruslabs/android-sdk:33 ./gradlew assembleDebug
```

Output APK: `build/outputs/apk/debug/QuickSettings-debug.apk`
