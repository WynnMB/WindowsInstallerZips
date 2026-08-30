# Windows Installer ZIPs

These archives are designed to create UEFI-bootable USB drives for Windows installation on non-Windows devices that cannot run Rufus.

The `install.wim` file has been converted to `install.esd` using DISM’s "Recovery" compression setting.

## Installation

1. Extract the ZIP archive.
2. Format the USB drive as FAT32, if it's not already.
3. Copy all items from the folder to the USB drive.
4. All done!
