# Unofficial OTA Repository

This repository hosts **unofficial OTA update** for supported devices.
It is intended to be used with custom ROM builds distributed outside of official
infrastructure.

## 📱 Supported Devices

- Xiaomi POCO F1 (beryllium)

## 📦 Repository Structure


Each JSON file inside `builds/` represents OTA metadata for a specific device.

## 🔄 OTA JSON Format

Each OTA JSON entry typically includes:

- ROM version
- Build date
- Download URL
- File size
- **MD5 checksum**
- **SHA256 checksum**

These fields are used by the ROM's built-in OTA updater to:
- detect new builds
- verify download integrity
- ensure safe installation

## ⚠️ Disclaimer

- This is an **unofficial OTA source**
- Builds are provided **as-is**, without any warranty
- Flash at your own risk
- The maintainer is **not responsible** for any data loss or device damage

## 🛠️ Maintainer
- Ky Thien (Jiro)
- GitHub: https://github.com/jiro28
- Telegram: https://t.me/ktdisscution

## 📜 License

This repository only contains OTA metadata (JSON files).
All ROM builds, binaries, and trademarks belong to their respective owners.
