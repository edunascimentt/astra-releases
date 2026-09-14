# Astra — releases

Builds of the Astra panel for Adobe Premiere Pro and After Effects. This repository holds only the packaged releases and the update manifest; the source code is not published here.

## Install

Download the installer for your system from the [latest release](https://github.com/edunascimentt/astra-releases/releases/latest):

- **Windows:** `Astra-Setup-<version>.exe`
- **macOS:** `Astra-<version>.pkg`

Then restart Premiere Pro or After Effects and open **Window → Extensions → Astra**. Later versions are installed by the panel itself.

The installers are not code-signed yet:

- **Windows:** SmartScreen may show "Windows protected your PC". Click **More info → Run anyway**.
- **macOS:** if the installer is blocked, open **System Settings → Privacy & Security** and click **Open Anyway**.

## Files

- `Astra-Setup-<version>.exe`, `Astra-<version>.pkg`: installers.
- `astra-<version>.zip` and `.sha256`: the package the in-app updater downloads.
- [`updates.json`](updates.json): the update manifest installed panels read. It is written by the publish script; do not edit it by hand.
