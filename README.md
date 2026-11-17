# Timberline downloads

A hardcore first-person survival game for PC. Early test builds: expect missing features and bugs.

## Download

- **Windows:** [Timberline-Windows.zip](https://github.com/TallTeezSteez/timberline-releases/releases/latest/download/Timberline-Windows.zip)

These links always get the newest version. Older versions: [all releases](https://github.com/TallTeezSteez/timberline-releases/releases).

**First time:**
1. Unzip the whole folder (right-click > Extract All), then double-click `Timberline.exe`.
2. If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**. You only do this once.

The game shows **Update available** on the main menu when there's a new version. Download the new zip and replace the old folder.

More about Timberline, with screenshots: https://draftlineapps.com/timberline

Saves and settings live in `%APPDATA%\Godot\app_userdata\Timberline`, so updating keeps them.

## How a new version goes out

Bump the version in the game files first, then: **Actions > Release > Run workflow**. Leave the version blank. It builds, tests and publishes on GitHub's free machines.

This repo is public so the downloads work for everyone. The app's code is in a private repo and isn't here.
