<div align="center">

# PuirkleQR

**Free QR code and barcode studio for Windows, macOS and Linux**

[![Latest version](https://img.shields.io/github/v/release/ResinCoreAI/PuirkleQR-Releases?label=latest&color=7c3aed)](https://github.com/ResinCoreAI/PuirkleQR-Releases/releases/latest)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-0a7bbb)
![Price](https://img.shields.io/badge/price-free-2ea44f)
![Languages](https://img.shields.io/badge/languages-English%20%7C%20Thai-f08c00)

🌐 **English** | [ภาษาไทย](README.th.md)

### [⬇️ Download the latest version](https://github.com/ResinCoreAI/PuirkleQR-Releases/releases/latest)

</div>

Hi! It's me, Puirkle 👋

I'm happy to share **PuirkleQR** with everyone. It makes QR codes and barcodes that look exactly the way you want, and it's completely free to use, **including for commercial purposes**. There are no hidden fees or paid features required.

This repository is the official home of PuirkleQR downloads, release notes and bug reports.

## 📦 Download

Open **[the latest release](https://github.com/ResinCoreAI/PuirkleQR-Releases/releases/latest)** and pick the file for your computer:

| Your computer | File to download |
|---|---|
| 🪟 Windows (install it) | `PuirkleQR-<version>-windows-installer.exe` |
| 🪟 Windows (no install, run from a folder or USB stick) | `PuirkleQR-<version>-windows-portable.zip` |
| 🍎 Mac with Apple chip (M1, M2, M3, …) | `PuirkleQR-<version>-macos-apple-silicon-portable.zip` |
| 🍎 Mac with Intel chip | `PuirkleQR-<version>-macos-intel-portable.zip` |
| 🐧 Linux (Ubuntu, Debian and similar) | `PuirkleQR-<version>-linux-installer.deb` |
| 🐧 Linux (other distributions) | `PuirkleQR-<version>-linux-installer.run` or `PuirkleQR-<version>-linux-portable.tar.gz` |

`PuirkleQR-FileServer.zip` is not the app. It's the optional server for [File QR](#-file-qr).

> [!TIP]
> Not sure which Mac you have? Open the Apple menu → **About This Mac**. **Chip: Apple M…** means an Apple chip; **Processor: … Intel …** means an Intel chip.

**You only need to download once.** PuirkleQR updates itself: when a new version is out, it asks **"Update now?"** the next time you open it. If the app ever acts up, **Studio menu → Reinstall this version…** installs it again over your copy, and your codes and settings stay.

## 🛠️ Install

<details>
<summary><b>🪟 Windows</b></summary>
<br>

- **Installer:** run `PuirkleQR-<version>-windows-installer.exe` and follow the steps.
- **Portable:** unzip `PuirkleQR-<version>-windows-portable.zip` into any folder (or a USB stick) and start PuirkleQR from that folder.
- If a blue **"Windows protected your PC"** window appears, click the **More info** link, then the **Run anyway** button.

</details>

<details>
<summary><b>🍎 macOS</b></summary>
<br>

1. Unzip the file for your Mac (Apple chip or Intel).
2. Open PuirkleQR.
3. If macOS says the app can't be opened or verified, go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

</details>

<details>
<summary><b>🐧 Linux</b></summary>
<br>

Replace `<version>` with the version number in the file you downloaded.

**Ubuntu, Debian and similar (.deb)**

```bash
sudo apt install ./PuirkleQR-<version>-linux-installer.deb
```

**Other distributions (.run)**

```bash
chmod +x PuirkleQR-<version>-linux-installer.run
./PuirkleQR-<version>-linux-installer.run
```

**Portable (.tar.gz):** no install, unpack it and start PuirkleQR from the new folder.

```bash
tar -xzf PuirkleQR-<version>-linux-portable.tar.gz
```

</details>

## 🔑 Free license

If PuirkleQR asks you for a license, don't worry, it's free! Use this one:

```text
PQR-HA2C-QJNJ-9PJB-DVRQ
```

**How to enter it:** click the plan button at the top right of the window, type the license, then press **Activate**.

You can also send me a DM on Discord and I'll give you a license for free: **pthemaid**

Without a license, PuirkleQR runs on the Free plan: codes get a watermark and some tools, such as the Card Maker, stay locked.

💡 You are also free to use PuirkleQR for commercial purposes.

## ✨ Features

PuirkleQR Studio makes QR codes and barcodes that look the way you want. It works offline, in Thai and English, with dark and light mode.

### 🔗 24 kinds of QR code

- **Web and text:** website link, plain text, app download (Google Play / App Store), file (PDF, picture, audio, video)
- **Contact:** vCard, MeCard, email, SMS, phone call, social profile
- **Chat:** WhatsApp, LINE, WeChat
- **Meetings:** Zoom, Google Meet, calendar event
- **Places and networks:** location, Wi-Fi
- **Payments:** PromptPay (Thai QR), TrueMoney Wallet, PayPal, WeChat Pay, crypto
- **Music:** Spotify

### 🎨 Design

- **Code shapes:** circle, heart, rounded square, octagon, hexagon, diamond, star, shield, flower, badge, speech bubble, map pin and cloud, with a border in any colour or none
- **17 body patterns**, 9 eye frames and 13 eye balls
- **Colours:** solid or multi-colour gradient, own colours for the eyes, transparent or rounded background
- **Logo in the middle:** 34 built-in icons, your initials, or your own picture
- **18 frames:** "Scan me" labels, speech bubble, ticket, Polaroid, phone, Thai QR Payment, stamp, or your own picture
- **Texts and stickers:** add texts and animated stickers anywhere on the code
- **Picture QR:** your photo or animated GIF inside the code
- **100 ready-made styles:** one click, including the "Shaped" and "Business" groups
- **Animated GIF codes:** rainbow flow, gradient flow, colour cycle

### 📊 Barcodes

Code 128, Code 39, Code 93, EAN-13, EAN-8, UPC-A, UPC-E, ITF, Codabar, PDF417, Data Matrix, Aztec

### 📚 Many codes at once

- **Multi QR:** QR Code tab → Content → **Multi QR…**. One row of text = one QR code, all with the same style, logo and frame, saved as separate files in the folder you choose
- **Multi barcode:** Barcode tab → **Multi barcode…**
- Type the rows or import a `.txt` / `.csv` file. Files are named from the row text or numbered (`qr-001`, `qr-002`, …), and existing files are never overwritten

### 🪪 Card Maker

Design ID cards, staff and student cards, event badges, member cards, business cards and name tags, then make one card for every person on a list (type it, paste from Excel or import CSV).

- Each box is **Fixed** or **Each person**: names, photos, QR codes and barcodes per person
- More than 20 templates, a custom size, or start from your own card picture
- Canva-like editing: drag, resize, rotate, align, layers, type on the card, Ctrl+Z / Ctrl+C / Ctrl+V, zoom and Focus mode
- Colours by level or position (e.g. Level A red, Level B blue), different texts, show / hide boxes, and recolouring of an imported card picture
- Auto running numbers with your own prefix, year, date or character set, with ready-made presets
- Projects are saved in the app automatically and can be exported as `.pqrcard` files. Save every card as PNG / JPG / SVG, or print at real size with cut guides

*The Card Maker needs a license (Individual plan or above). It's free, see [🔑 Free license](#-free-license).*

### ✅ Scan check

Every code is test-read while you design it, so you know it scans before you print it.

### 💾 Save, print, share

- **Save as** PNG, JPG, BMP, SVG (vector) or animated GIF, up to 32,768 px for posters
- **Print designer:** many codes on one page, sticker sheets, auto arrange, A3 to A6 and more
- **My QR:** keep your codes in groups, edit them later, reuse their style
- **Share:** copy, email, LINE, WhatsApp, Telegram, Facebook, X
- **Send to your other computers** on the same network, no internet needed

### 💼 Portable version

Runs from a folder with no installation. Your data stays in one encrypted file that only opens on your PC, and there is a **Move to another PC** button for when you change computers.

### 📁 File QR

A QR code that opens a PDF, picture, song or video. The file is uploaded to storage you own: your own file server or S3-compatible storage. `PuirkleQR-FileServer.zip` in every release is a small file server for File QR that runs on PHP web hosting or as a Cloudflare Worker.

## 🆕 What's new

**1.1.1**

- Opens about 4 times faster (about 1 second instead of 5), with a logo splash while it starts
- No freezes after start: the other tabs and the preview pictures are prepared in the background, so switching tabs is instant
- Uses less memory: moving style previews are drawn only when shown
- Card Maker: new "Security access card" template

**1.1.0:** new **Card Maker** tab (see [Features](#-card-maker))

<details>
<summary>Earlier versions</summary>
<br>

| Version | Highlights |
|---|---|
| 1.0.9 | Multi QR and Multi barcode: many codes at once |
| 1.0.8 | Studio menu → **Reinstall this version…**; full-width "Shape border" slider; "Round corners" explains when it has no effect |
| 1.0.7 | 11 more code shapes, shape border in any colour, 30 more style presets; license checked at start and every 30 minutes |
| 1.0.6 | QR for Zoom and Google Meet; circle and heart code shapes; the Free plan watermark now runs across the code (it still scans) |
| 1.0.5 | File QR; QR for LINE, WeChat, PayPal, WeChat Pay, Spotify and app-store links |
| 1.0.4 | Version number in the window title; clear messages when a folder can't be written to or your plan can't save GIFs |
| 1.0.0 | First version |

</details>

Full notes for every version: **[Releases](https://github.com/ResinCoreAI/PuirkleQR-Releases/releases)**

## 🐞 Found a bug?

Tell me here: **[Issues](https://github.com/ResinCoreAI/PuirkleQR-Releases/issues)** (there is also a **Report a bug** button in the app).

It helps a lot if you include your PuirkleQR version (it's in the window title) and your system, e.g. Windows 11, macOS 15 or Ubuntu 24.04.

## ☕ Support my work

The "paid version" is basically a joke 😂

However, if you enjoy my software and would like to support me, you can do so here:

- 🇹🇭 **Thai support** (Thai only): https://ezdn.app/puirkle
- ☕ **Buy Me a Coffee:** https://buymeacoffee.com/puirkle

## ❤️ Thank you!

Thanks for using PuirkleQR and supporting my work! Your support helps me continue making and maintaining free software.

— Puirkle
