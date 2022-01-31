# auto-update_clean

## Purpose:
- Get system update.
- Upgrade the system.
- Remove and clean apt packages that were automatically installed because some other packages required them, but were eventually removed.
- Cleans out cache accumulated after installing packages using `apt-get install`
- Removes older versions of snaps.

## Usage:
- Download the `upgrade_clean.sh` file
- Add executable permission to the file using `chmod +x upgrade_clean.sh`
- Run the file as an executable: `./upgrade_clean.sh`
- If it fails, run as a superuser using: `sudo ./upgrade_clean.sh`

## Use Cases:
**Currently, this bash script for Debian based operating systems and has been particularly used and tested on Ubuntu 20.04.3 LTS**

- Update and upgrade the system with ease.
- Clean and unclutter the system.
- Free up disk space.
