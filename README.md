# Eaves 🪶

**Eaves** is a "headless" high-fidelity audio recorder designed for speed, minimalism, and stealth.

## Features
* **Zero Interface:** No screens, no menus, no loading times.
* **One Tap:** Tap the icon to start recording instantly in the background. Tap again to save.
* **Studio Quality:** Captures crystal-clear AAC audio at 192kbps directly to your local storage.
* **Invisible:** Runs silently with only a system-required notification.

## Usage & Warnings ⚠️
* **No Recording Limit:** Eaves does **not** have a time limit. It will continue recording indefinitely until you tap the icon to stop it or until your device runs out of storage.
* **Always On:** Recording continues seamlessly even if your **screen is locked** or while you use other apps.

## Pro Tip: True Stealth 🥷
By default, Android forces a notification to show when the microphone is in use.
* **To make Eaves completely invisible:** Go to your phone's **App Info > Notifications** for Eaves and switch them **OFF**.
* *Result:* The recording notification will vanish, and the app will record with absolutely no visual sign on the screen.

## How it Works
1. **Tap to Start:** The app launches, starts a foreground service, and immediately closes the UI.
2. **Recording:** A subtle notification indicates the microphone is active (unless disabled).
3. **Tap to Stop:** Tapping the icon again stops the service and saves the file.
4. **Storage:** Files are saved safely to `/Internal Storage/Music/Eaves/`.

## Why isn't this on the Play Store?
Eaves is a custom-built utility, not a commercial product. The Google Play Store requires all apps to have visible user interfaces. Because Eaves is designed to be a "Power Tool"—bypassing screens for instant capture—it deliberately breaks those UI rules.

## Installation
Go to the [Releases](https://github.com/RyuunAkasa/Project-Eaves-Android-/releases/latest) page to download the latest APK.