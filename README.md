# Disk Tools for Android

Magisk module that installs disk partitioning tools for Android. Installs `fdisk`, `sfdisk`, `cgdisk`, `gdisk`, `sgdisk`, `fixparts`, and `parted` to `/system/bin/` via Magisk's systemless overlay.

Tools included:
- **fdisk**, **sfdisk** — from [util-linux](https://github.com/util-linux/util-linux)
- **cgdisk**, **gdisk**, **sgdisk**, **fixparts** — from [GPT fdisk](https://sourceforge.net/projects/gptfdisk/)
- **parted** — from [GNU Parted](https://www.gnu.org/software/parted/)

## Prerequisites

- Android device with [Magisk](https://github.com/topjohnwu/Magisk) v20.4+ installed
- Architecture: aarch64

## Installation

### From release (recommended)

1. Download the latest `disk-*.zip` from the [releases page](https://github.com/evdenis/disk/releases)
2. Open **Magisk** → **Modules** → **Install from storage** → select the zip → **Reboot**

Supports auto-update via Magisk's built-in update mechanism.

### From source

```bash
git clone https://github.com/evdenis/disk
cd disk
make install
```

Requires `adb` with USB debugging enabled and root access on the device.

## Support

- [Telegram](https://t.me/joinchat/GsJfBBaxozXvVkSJhm0IOQ)
- [XDA Thread](https://forum.xda-developers.com/apps/magisk/module-debugging-modules-adb-root-t4050041)
