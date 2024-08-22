![image](https://raw.githubusercontent.com/AshiVered/support-israel-banner/main/assets/support-israel-banner.jpg)


# TitanPad - simple and lightweight keyboard app for Unihertz Titan Pocket and compatible keypad Android phones
Forked from https://github.com/AshiVered/TitanPad.
# Features

- Two layouts: Engish and Hebrew (modified from the AshiVered layouts).
- Layout switching with `alt` key; Caps switching with `shift` key.
- Special character input with `sym` key.
- Non-invasive passing input control to the system in number entry fields.


# Building

The app project is compatible with Android Studio 3.3.2. Just clone the repo, import the project and build it with the Studio distribution.

# Installation/Update

Enable Developer settings and USB debugging. Then run:

```
adb install [your_built_apk]
```

To update the version, run:

```
adb uninstall aiv.ashivered.titanpad
adb install [your_new_apk]
```

# Initial setup

Launch the app. You'll be taken to the standard Android input method selection dialog. Select TitanPad and deselect the stock keyboard.

You'll need to setup after each version update.
