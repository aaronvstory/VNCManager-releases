# VNC Manager

See and control your jailbroken iPhones from one window on your PC or Mac, over USB or WiFi.

This repo holds the installers and release notes. The app updates itself from here.

## Install

1. Open the [latest release](https://github.com/aaronvstory/VNCManager-releases/releases/latest).
2. Download the file for your computer:
   - **Windows:** `VNCManager-<version>-win-x64.exe`
   - **Mac (Apple silicon):** `VNCManager-<version>-mac-arm64.dmg`
3. Run the file.

**Already have an older version?** Install the new one over it. Your phones and settings stay.

The builds are not signed with a paid certificate:

- **Windows:** if SmartScreen appears, click **More info**, then **Run anyway**.
- **Mac:** if macOS blocks the app, right-click it and choose **Open**.

## What you need

- An iPhone with a jailbreak and the [TrollVNC](https://github.com/OwnGoalStudio/TrollVNC) server. The app can install TrollVNC for you from **Phone setup**.
- The phone must trust this computer for USB, or be on the same WiFi network.

Phones with no jailbreak do not work. If one keeps showing under **Detected**, click its **X** to ignore it. You can undo this in **Settings**.

## Updates

The app checks for a new version at launch and once a day. When one exists, an **Update** button shows in the top bar. Click it, and the app installs the update and restarts.

**Version 7.4.3 or older:** the old update check cannot see this repo, and it can say that you have the latest version. Install the newest version by hand one time. Updates are automatic after that.

## Tips

- **Smooth swipes on WiFi:** open **Phone setup** and choose **Smooth**. In **Settings**, lower **Focus quality · WiFi**. USB is always the smoothest.
- **Paste:** copy on the computer, then press Ctrl+V (Cmd+V on a Mac) on the phone stream. iOS can ask you to allow the paste. You can set **Allow** for each app in the iPhone's settings.
- **Other shortcuts:** Ctrl (Cmd on a Mac) plus a key goes to the phone as Command plus that key.
- **Open in:** the lime button opens the phone in an external viewer such as RealVNC.
- **Smaller window:** click the panel button next to the version to hide the device list.

## Problems

Open an [issue](https://github.com/aaronvstory/VNCManager-releases/issues). Include your app version, which shows next to the logo at the top left.
