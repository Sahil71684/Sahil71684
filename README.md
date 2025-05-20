- 👋 Hi, I’m @Sahil71684
- 👀 I’m interested in ...Bringing together all platforms
- 🌱 I’m currently learning ...nothing, I work fulltime. This is a hobby.
- 💞️ I’m looking to collaborate on ...Any new projects. I dont know much I just hit links.
- 📫 How to reach me ...Call me 5712355181 7035827728 5712683319.

# Sequoia Resurrection
**macOS Sequoia (15 Beta) running on a Late 2013 MacBook Pro – Fully Functional “God Mode” Setup**

![screenshot](https://your-image-link.com) <!-- Optional: Add real screenshot later -->

## Overview

This project documents the successful installation and full operation of macOS 15 Sequoia on an **unsupported MacBook Pro 15-inch (Late 2013)**, model **MacBookPro11,3**, using OpenCore Legacy Patcher (OCLP). Contrary to Apple's official support list, this machine now runs Sequoia **flawlessly**, complete with full system acceleration, App Store, and root access.

> **First Fully Stable Sequoia Install on MacBookPro11,3? Possibly. Definitely worth bragging.**

---

## System Specs

| Component       | Details                         |
|----------------|----------------------------------|
| Model           | MacBookPro11,3 (Late 2013)      |
| CPU             | Intel Core i7                   |
| RAM             | 16 GB                           |
| Storage         | Samsung 990 Pro 2TB NVMe (via Sintech adapter) |
| macOS Version   | macOS Sequoia 15.x Beta         |
| Patch Tool      | OpenCore Legacy Patcher vX.X.X  |
| EFI Spoof       | MacBookPro16,1                  |
| Root Status     | Full SIP/AMFI disabled (God Mode) |

---

## What Was Done

- **Used OpenCore Legacy Patcher** to spoof model → `MacBookPro16,1`
- Installed macOS Sequoia from USB Installer
- Mounted EFI at `disk0s1` and patched OpenCore manually
- Disabled:
  - System Integrity Protection (SIP)
  - Secure Boot
  - FileVault
  - Apple Mobile File Integrity (AMFI)
- Enabled full **root-level customizations**
- Fixed missing system apps (Pages, Keynote, Numbers)
- Installed third-party tweaks (MacForge-ready)
- Performance is **buttery smooth**, with no graphical glitches

---

## Why It Matters

- Apple officially blocks Sequoia on Macs older than 2018
- This Mac was not supposed to support even Ventura natively
- Yet here it is, running the **latest beta like a modern M1**
- **No kernel panics, no hacks breaking updates, just smooth power**

---

## Screenshots

_Optional: Add screenshots here_
- System Info showing Sequoia and model spoof
- MacForge or OCLP showing status
- Dock and Launchpad after fixes

---

## Credits

- **@Sahil71684** – Project owner and system modder  
- ChatGPT – Tech support and system patch strategist  
- OpenCore Legacy Patcher Team – Open-source MVPs  
- Mac community for inspiration and guidance

---

## License

This is a personal project for educational and legacy system preservation purposes. No warranty, no support, just pure skill.

---

## Note

If you want to replicate this, know what you’re doing. You’ll be disabling major security features and entering deep system-level customization.
