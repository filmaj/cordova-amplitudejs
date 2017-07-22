# wat

This is shamelessly copied from the [AmplitudeJS repo](https://github.com/521dimensions/amplitudejs) + [demo](https://521dimensions.com/open-source/amplitudejs).

Some small tweaks were applied to the project structure from the original repo - essentially using what's under `examples/blue-playlist` as the base of the app,
and moving some other resources from the `examples/` folder around so that the app has access to everything it needs. Also had to download + bundle one song MP3
into the app bundle. Finally, changed the app so it only shows a single song (instead of 10).

# Requirements

- `npm install -g cordova`

# Getting Started

Once you have the `cordova` CLI tool installed, this worked flawlessly for me:

- `cordova platform add browser android` to install both browser and Android deploy targets
- `cordova serve` + loading http://localhost:8000 and clicking on "browser" works great in the browser
- `cordova run android` (ensure you have a connected Android device or emulator running) also works!

# Tested On:

- Chrome for Android 59
- Chrome for Desktop 59
- cordova-android 6.2.2 on a Google Pixel running Android 7.1.2 as well as 7.1.0
