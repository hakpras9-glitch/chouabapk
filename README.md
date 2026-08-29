# Fruit Ninja CV Bot

Android starter project for an on-device Fruit Ninja automation bot.

## What it does
- Captures the screen using Android MediaProjection.
- Finds bright/saturated regions using a lightweight color detector.
- Uses an AccessibilityService to perform swipe gestures.

## Important
This is a starter implementation, not a guaranteed working Fruit Ninja bot.
The detector is deliberately simple and can mistake UI elements or fruit for other objects.
A safer production detector should use connected components and a fruit/bomb classifier.

## Build
Open this folder in Android Studio, let Gradle sync, then build the APK.

## Phone setup
1. Install the debug APK.
2. Open the app.
3. Enable its Accessibility service.
4. Grant screen-capture permission.
5. Open Fruit Ninja.
6. Start the bot.

Use only where automation is permitted by the game's rules.
