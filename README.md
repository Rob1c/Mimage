<table>
  <tr>
    <td width="200">
      <img src="mimage.png" width="200" alt="Welcome to Mimage!">
    </td>
    <td>
      <h1>Mimage -  Simplest CLI Floppy Image Converter</h1>
      <img src="https://github.com/Rob1c/Mimage/actions/workflows/build.yml/badge.svg" alt="Build Status">     
      <img src="https://img.shields.io/badge/version-1-blue" alt="Version">
      <img src="https://img.shields.io/badge/license-CC-BY-NC-4.0" alt="License"> 
      <img src="https://img.shields.io/badge/-Windows-0078D6?logo=windows&logoColor=white" alt="Windows">
      <img src="https://img.shields.io/badge/platform-Debian%20|%20Ubuntu-orange" alt="Platform">
    </td>
  </tr>
</table>

---

## Purpose
Mimage is a CLI floppy image to stream files (.raw) converter. 

It was created to greatly simplify the delicate process of converting floppy disk images into stream files for low-level writing. Mimage is useful for quick conversions and then writing floppies for all kinds of vintage machines (don't let the logo alone convince you!) using cards like Greasweazle or Kryoflux.

It basically acts as a simple wrapper for the CLI tool "Macintosh.exe" by ZrX, also included in the main branch.
## ⚖️ License Compliance

This project adopts a mixed license structure to ensure maximum transparency:

- Mimage Script & Packaging: Released under the CC BY-NC 4.0 license.

- ```Macintosh.exe```: Copyright by [ZrX](https://forum.kryoflux.com/memberlist.php?mode=viewprofile&u=1054) (Kryoflux Forums). Included as "custom-freeware" for compatibility purposes.

Refer to the LICENSE.txt and debian/copyright files for full details.

## 📦 Package Details

- **Latest Version**: `1.0.1`
- **Architecture**: `x86_64 (amd64)`
- **Dependencies**: `wine` | `wine64` | `wine32`
- **Install location**: `/usr/bin/`

## Installation
Via apt (**recommended**, because it automatically resolves dependencies):
```bash
sudo apt install ./mimage-[version]-deb.deb
```
Or via dpkg:
```bash
sudo dpkg -i ./mimage-[version]-deb.deb
```
## Compatibility
This package was developed and tested under `Debian 13 "Trixie" (Stable)`, but it should work fine under every debian-based system.

## 🤝 Willingness to Collaborate
If ZrX ever gets to know Mimage, it would be an honor first of all to thank him, and then hope for a strong collaboration!

## Feedback & Contributions
If you encounter issues or have suggestions, feel free to open an issue in this repository. You may also consider submitting feedback to [the official Ghidra GitHub](https://github.com/NationalSecurityAgency/ghidra) repository if relevant.
