# TravelerOS

TravelerOS is a lightweight and stable linux distribution based on Q4OS, which is Debian based. It is built for USB drives, and not hard drives. TravelerOS comes with KDE Plasma 6. TravelerOS is customized to be a portable linux distribution meant for USB drives, although you could boot it from a CD, or SD card, if possible. TravelerOS is also a bit lightweight, only taking up as low as 800 MB of RAM. If you want it to be lower, consider installing TravelerOS Lite, for old computers. TravelerOS is also very customizable, thanks to KDE Plasma, with that, you can customize the start menu, the panel, the window, the icons, anything! Since TravelerOS is portable, even if you boot the USB drive in a different computer, it still works the same! TravelerOS is meant for users who want to try/use linux, without installing it to the hard drive, meaning that you can store apps, games, documents, and other stuff without it erasing on reboot. TravelerOS is also meant for users who need help with their hard drive or their current operating system, like fixing the bootloader, partitioning the disk, removing a partition, or erasing the whole disk.

## System Requirements

- **Architecture**: x86_64 (x32 for TravelerOS Lite)
- **RAM**: 1 GB minimum (2 GB recommended)
- **Storage**: 4 GB USB stick or larger (For more than 16 GB of persistent storage, you need a 32 GB or larger USB stick.)
- **Graphics**: Works with most integrated and legacy GPUs

## How to Install

1. Download the latest ISO from the [Releases](https://github.com/traveler-usb/TravelerOS/releases)
2. Flash it to a USB drive using [Rufus](https://rufus.ie) or for linux users, follow this [short guide.](
3. Boot from USB and when "Start a new session" is highlighted, press E on your keyboard, and go to the end of the APPEND section, and put in the following paremeter:
  perchsize=??000 (**THIS IS ONLY FOR USB DRIVES THAT ARE 32 GB OR LARGER, IF YOUR USB DRIVE IS LESS THAN 32 GB, JUST SELECT "Start a new session" BY PRESSING ENTER.**)
  Here's an example:
If you have a 32 GB USB drive, you can put **perchsize=20000** so that way you have 20 GB of storage, and 12 GB for save files.

## Credits
**TravelerOS wouldn't be a thing if it weren't for these softwares:**

[Slax](https://www.slax.org)
[Linux Live Kit](https://www.linux-live.org/)
[Q4OS](https://q4os.org/)
[KDE Plasma](https://kde.org/plasma-desktop/)
[MiniOS](https://minios.dev/)

---


