<table>
  <tr>
    <td width="200">
      <img src="mimage.png" width="200" alt="Welcome to Mimage!">
    </td>
    <td>
      <h1>Mimage -  Simplest CLI Floppy Image Converter</h1>
      <img src="https://github.com/Rob1c/Mimage/actions/workflows/build.yml/badge.svg" alt="Build Status">     
      <img src="https://img.shields.io/badge/version-1-blue" alt="Version">
      <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg" alt="CC-BY-NC 4.0">
      <img src="https://img.shields.io/badge/-Windows-0078D6?logo=windows&logoColor=white" alt="Windows">
      <img src="https://img.shields.io/badge/-Debian%20|%20Ubuntu-orange" alt="Debian/Ubuntu">
      <img src="https://img.shields.io/badge/-MacOS-grey" alt="MacOS">
    </td>
  </tr>
</table>

---

## Purpose
Mimage is a CLI floppy image to stream files (.raw) converter. 

It was created to greatly simplify the delicate process of converting floppy disk images into stream files for low-level writing. Mimage is useful for quick conversions and then writing floppies for all kinds of vintage machines (don't let the logo alone convince you!) using cards like Greasweazle or Kryoflux.

It basically acts as a simple wrapper for the CLI tool "Macintosh.exe" by ZrX, also included in the main branch.

## Need a simple and comprehensive how-to guide? I've created one specifically for you. It's for Macintosh, but it works equally well on other formats and machines.

[Take a look!](https://www.reddit.com/r/VintageApple/comments/1t0pupi/how_to_create_a_35_floppy_for_classic_macs_with/)

## ⚖️ License Compliance

This project adopts a mixed license structure to ensure maximum transparency:

- Mimage Script & Packaging: Released under the CC BY-NC 4.0 license.

- ```Macintosh.exe```: Copyright by [ZrX](https://forum.kryoflux.com/memberlist.php?mode=viewprofile&u=326) (Kryoflux Forums). Included as "custom-freeware" for compatibility purposes.

Refer to the LICENSE.txt and debian/copyright files for full details.

## 📦 Package Details

- **Architecture**: `x86_64 (amd64)`
- **Dependencies**: `wine` | `wine64` | `wine32`
- **Install location**: `/usr/bin/`

## Installation
## Debian | Ubuntu (.deb package) 
Via apt (**recommended**, because it automatically resolves dependencies):
```bash
sudo apt install ./mimage-[version]_all.deb
```
Or via dpkg:
```bash
sudo dpkg -i ./mimage-[version]_all.deb
```
## Windows and MacOS
Because Mimage is written in Unix Bash, you can run the executable on MacOS, but not on Windows, unless you use an emulator.

To get around this, there's a very simple solution. Just download the original `Macintosh.exe` and run it conveniently from the terminal.

## Usage
```bash
mimage [diskimagename] [outputdirectory]/[streamfilename]
```
Example:
```bash
mimage myfloppy.img myfloppyraw/track
```
Mimage will generate several .raw files. It's strongly recommended to use an output directory.

## Compatibility
This package was developed and tested under `Debian 13 "Trixie" (Stable)`.
See "Installation" for cross-platform compatibility information.

## 🤝 Willingness to Collaborate
If ZrX ever gets to know Mimage, it would be an honor first of all to thank him, and then hope for a strong collaboration!

## Feedback & Contributions
If you encounter issues or have suggestions, feel free to open an issue in this repository. You may also consider submitting feedback to [the official Ghidra GitHub](https://github.com/NationalSecurityAgency/ghidra) repository if relevant.
