# Zcalendar

**English** | [简体中文](README.zh-CN.md)

A personal desktop calendar for Apple Silicon Mac. Plan your schedule, organize priorities, and view or share your time. Available in English and Simplified Chinese.

## Download Zcalendar

### [⬇ Download for macOS · v0.8.6 (DMG)](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/Zcalendar-0.8.6-macOS-arm64.dmg)

[Download ZIP](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/Zcalendar-0.8.6-macOS-arm64.zip) · [Release notes & all files](https://github.com/ZaneLi11/Zcalendar/releases/tag/v0.8.6) · [All releases](https://github.com/ZaneLi11/Zcalendar/releases)

**For Apple Silicon Macs (M-series), with a declared minimum of macOS 13.0.** This package does not support Intel Macs or Windows. Compatibility with other Macs and the minimum macOS version has not been tested on additional hardware. The DMG and ZIP are about 129 MB each and contain the same app; choose either one.

## Features

- **Plan your schedule:** Create and edit events, set reminders, and repeat events weekly, monthly, or yearly.
- **Explore your time:** Switch between month, week, and day views, with timeline views for browsing and adjusting your day or week.
- **Focus on priorities:** Assign high, medium, or low priority, customize colors, search events, and make changes in batches.
- **Share and back up:** Export to PDF, PNG, JSON, or Markdown, and create or restore complete calendar backups.
- **Connect AI when you choose:** Connect a compatible AI client through the local MCP service, or import AI-generated schedule proposals for review and confirmation.

Calendar data is stored on your computer. If you enable AI access, grant only the permissions you need and review your AI client's data handling practices.

## Installation

1. Download the **DMG installer** above.
2. Open it and drag **Zcalendar** to **Applications**.
3. Launch Zcalendar from Applications. When updating, quit the existing app completely before replacing it.

If you prefer the ZIP, extract it and move `Zcalendar.app` to Applications.

### First launch

This release is ad-hoc signed. It does not yet have a Developer ID signature or Apple notarization, so macOS may block the first launch after download. Once you have verified the download source, follow [Apple's official guidance](https://support.apple.com/en-us/102445) to find **Open Anyway** in **System Settings → Privacy & Security**.

### Verify your download

Download [SHA256SUMS.txt](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/SHA256SUMS.txt) into the same folder as the installer, then run this command from that folder:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

The checksum file lists both the DMG and ZIP. If you downloaded only one, the other will be reported as missing; the file you downloaded should show `OK`.

[Full installation guide (English & Chinese)](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/INSTALL.md) · [Package audit record](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/release-info.json)

## About this repository

This repository distributes Zcalendar installers, release notes, and usage information. Project source files are not currently provided. Installers retain the JavaScript, native libraries, third-party dependencies, and licenses required to run the app; runtime code can still be extracted.
