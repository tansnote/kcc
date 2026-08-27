# 🔑 KCleaner — Keychain Management Tool for iOS

English | [简体中文](README.zh-CN.md)

KCleaner is a tool for managing local Keychain items created by apps on iOS. It makes it easy to create, edit, delete, and export Keychain items created by any app, helping you address issues related to app tracking or device bans. Unlike Keychain Access on macOS, KCleaner can access all local Keychain items, even when the developer has not enabled Keychain syncing.

## Features

- Delete all Keychain items
- Delete Keychain items that match a keyword
- View and delete Keychain items created by individual apps
- Inspect the contents of Keychain items created by apps
- Export and import an app's Keychain items
- Remove Keychain items left behind by uninstalled apps
- Block OTA updates for iOS and accessories
- Set a custom battery health value
- Clear NVRAM variables
- Remove the signed-in Apple ID
- Force a factory reset
- Prevent third-party apps from registering as Hotspot Helpers and launching automatically after connecting to Wi-Fi
- Clean iOS cache files and block the related daemons
- Reset the device advertising identifier (IDFA) and identifier for vendor (IDFV)

## Installation

### TrollStore

Download the latest `kcc.tipa` file from [Releases](https://github.com/tansnote/kcc/releases) and install it with TrollStore. This package supports TrollStore only.

### Jailbroken iOS 13 devices

Download the latest `kcc.deb` file from [Releases](https://github.com/tansnote/kcc/releases) and install it on a jailbroken iOS 13 device. This package supports jailbroken iOS 13 devices only.

> [!IMPORTANT]
> If you are trying to resolve a device ban, clearing the Keychain and app data alone is not enough. You also need to uninstall the app itself and restart the device once. This resolves most cases because device fingerprinting can use more than one method.

> [!NOTE]
> If iCloud Keychain syncing is enabled, turn it off first to prevent cloud data from being downloaded to the device again.

## Preview

![KCleaner screenshot 1](1.jpg)
![KCleaner screenshot 2](2.jpg)
![KCleaner screenshot 3](3.jpg)

## Contact

WeChat official account: `Tansnotes`

![WeChat official account QR code](wx.png)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=tansnote/kcc&type=Date)](https://star-history.com/#tansnote/kcc&Date)
