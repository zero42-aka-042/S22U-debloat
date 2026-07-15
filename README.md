# S22U-debloat
This is a extreme debloat guide for the samsung galaxy S22 ultra


## WARNING ⚠️ 
This is a extreme debloat intended for experienced users. It removes core Samsung applications (Camera, Gallery, Dialer, Contacts, Setup Wizard, etc.) and may break stock functionality. Use only if you understand how to recover your device.

**Tested on**

- Samsung Galaxy S22 Ultra
- BeyondROM
- Android 16

## Overview

This repository contains a package list intended for use with **Canta**.

The configuration removes a large number of Samsung and Google applications and services in order to create a minimal system. Unlike conservative debloat lists, this profile intentionally removes several stock applications that are normally expected to be present.

Review the package list before applying it.

## Requirements

* Samsung device running One UI
* Canta
* Root or Shizuku

## Scope

The configuration removes components including, but not limited to:

* Samsung applications
* Samsung cloud services
* Bixby
* Samsung AI features
* Samsung Themes
* AR Emoji
* Game Launcher / GOS
* Smart Switch
* Google consumer applications
* Various telemetry and optional services

Several core applications are also removed, including Samsung Camera, Gallery, Dialer and Contacts.

## Usage

Download the JSON configuration from the Releases page and import into Canta, review the package list before uninstalling.

Package removal is performed for the current user and is generally reversible.

## Restoring packages

Packages removed with `pm uninstall --user` or Canta can usually be restored using:

```sh
cmd package install-existing <package_name>
```

## Warning

This configuration is intended for advanced users.

It may remove functionality expected by One UI, Samsung applications or third-party software. Compatibility with OTA updates, Knox features, banking applications and Samsung ecosystem services is not guaranteed.

The maintainer assumes that users understand the implications of removing system packages.

## Contributing

Pull requests correcting package classifications, dependencies or compatibility issues are welcome.

## Useful Links

- [Canta](https://github.com/samolego/Canta)
- [Shizuku](https://github.com/RikkaApps/Shizuku)
- [F-Droid](https://f-droid.org)
