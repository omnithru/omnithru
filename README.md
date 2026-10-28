<p align="center">
  <img src="omnithru-logo.png" width="128" height="128" alt="Omnithru">
</p>

<h1 align="center">Omnithru</h1>
<p align="center"><strong>MIDI from any screen.</strong><br>
Turn phones, tablets and computers into MIDI controllers for your DAW, over your local network.</p>

<p align="center">
  <a href="https://omnithru.com">Website</a> ·
  <a href="https://omnithru.com/guide">Guide</a> ·
  <a href="https://github.com/omnithru/omnithru/releases/latest">Download</a> ·
  <a href="https://omnithru.com/it/">Italiano</a>
</p>

---

This repository hosts the **downloads** of Omnithru. The source code is not public.

## Download

Install Omnithru only on the computer with the MIDI ports (usually the one running your DAW).
Phones, tablets and other computers install nothing: they open Omnithru in the browser.

| System | File |
|---|---|
| Windows 10 and 11 (64 bit) | [Omnithru-Setup.exe](https://github.com/omnithru/omnithru/releases/latest/download/Omnithru-Setup.exe) |
| macOS 11 or later, Apple Silicon | [Omnithru-macos-arm64.dmg](https://github.com/omnithru/omnithru/releases/latest/download/Omnithru-macos-arm64.dmg) |
| macOS 11 or later, Intel | [Omnithru-macos-x64.dmg](https://github.com/omnithru/omnithru/releases/latest/download/Omnithru-macos-x64.dmg) |

Remote scripts for Ableton Live (only needed for the Clip Launcher):

| Ableton Live | File |
|---|---|
| 11 and later | [css_omnithru.zip](https://github.com/omnithru/omnithru/releases/latest/download/css_omnithru.zip) |
| 9.5 to 10.x | [css_omnithru-2_7.zip](https://github.com/omnithru/omnithru/releases/latest/download/css_omnithru-2_7.zip) |
| 9.5 and earlier | [css_omnithru-2_5.zip](https://github.com/omnithru/omnithru/releases/latest/download/css_omnithru-2_5.zip) |

Every release also has a `SHA256SUMS.txt` file to check the downloads.

## First start

Omnithru is made by an independent developer and the installers are not signed yet, so the first time:

- **Windows** shows *Windows protected your PC*: choose **More info → Run anyway**.
- **macOS** says it cannot verify the app: open **System Settings → Privacy & Security** and choose **Open Anyway**.
- **Phones and tablets** show a certificate warning: Omnithru creates its own HTTPS certificate for your computer. Choose **Advanced → Proceed**.

Details in the [guide](https://omnithru.com/guide#warnings).

## Requirements

- **Receiver** (the computer with the MIDI ports): Chrome or Edge, for the Web MIDI API.
- **Controllers**: any recent browser on phone, tablet or computer.
- All devices on the **same network**. No internet connection needed.

## Help and contact

- Guide and troubleshooting: <https://omnithru.com/guide>
- Bug reports and questions: [Issues](https://github.com/omnithru/omnithru/issues) or <info@omnithru.com>

## License

Omnithru is **free**, also for work: in the studio, on stage or in teaching.
It is **not open source**: you may not modify it, redistribute it or offer it as a service to others.
See [LICENSE](LICENSE) and <https://omnithru.com/license>.

© 2026 Francesco Laguardia. MIDI is a registered trademark of The MIDI Association. Ableton Live is a trademark of its owner. Omnithru is not affiliated with or endorsed by them.
