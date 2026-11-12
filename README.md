# Vortex

**Local-First Desktop Workbench for Engineers, Technical SEOs, Analysts & Power Users**

CrawlDeck &bull; RankPulse &bull; DevStation &bull; Universal Queue &bull; OmniDrop &bull; Visual Workflows &bull; FFmpeg Media Suite

[**Download Latest Release**](https://github.com/hamzaiqbal35/vortex-releases/releases/latest) 

---

## Downloads (Windows & Linux) ![GitHub Downloads](https://img.shields.io/github/downloads/hamzaiqbal35/vortex-releases/total)

Visit the [**Releases**](https://github.com/hamzaiqbal35/vortex-releases/releases/latest) page and pick the package for your system:

| Platform | File | Notes |
| :--- | :--- | :--- |
| **Windows 10/11 (Recommended)** | `Vortex Setup X.Y.Z.exe` | Standard NSIS installer; supports in-app updates via **Settings -> Check for Updates** |
| **Windows Portable** | `Vortex X.Y.Z.exe` | Zero-install executable (manual updates) |
| **Linux (Universal)** | `Vortex-X.Y.Z.AppImage` | `chmod +x Vortex-*.AppImage` then run; supports in-app updates |
| **Linux (Debian / Ubuntu)** | `Vortex_X.Y.Z_amd64.deb` | Install via `sudo apt install ./Vortex_*.deb` |

> **Windows SmartScreen Note (Early Unsigned Builds):** Windows may display *"Windows protected your PC"* while publisher reputation builds. Click **More info** -> **Run anyway**. Checksums for every binary are provided in `SHA256SUMS-windows.txt` and `SHA256SUMS-linux.txt`.

---

## Core Modules Included

* **CrawlDeck:** Dual-engine visual web scraper (Static Cheerio HTTP + Dynamic Headless Chromium), Auto-Detect Schema, Inspect Page DOM modal, Lightbox Gallery, direct CSV Cleaner handoff, and multi-format export (`CSV`, `JSON`, `NDJSON`, `Markdown`).
* **RankPulse (9-Workstation SEO Workbench):** Offline/localhost & production auditor covering Page Audit, Content & Focus Keyphrase, SERP/Social Previews, Heading Tree, Schema.org JSON-LD Validator, Robots.txt & XML Sitemap Simulator, Broken Link Spider, AI/LLM Readiness (GEO), and 8-Phase Playbook.
* **DevStation:** Wi-Fi LAN Sentinel, DNS & reverse PTR lookup, Ping telemetry, CIDR Subnet calculator, Multi-Port Scanner, SSL/TLS Certificate inspector, Offline JWT Debugger, Regex Sandbox, Cyber Decoder & AES-256-GCM Cipher Studio, HTTP Repeater, Security Headers Linter, Streaming File Checksums, and Ed25519/RSA SSH Key Pair generator.
* **Workflows:** Visual node pipeline builder (`Import CSV`, `URL Fetcher`, `Smart Match`, `yt-dlp Downloader`, `Folder Scanner`, `Filter`, `Batch Converter`, `Video Compressor`, `Renamer`, `Metadata Writer`, `Organize Files`).
* **Universal Download Queue & Browser Extension:** 8-chunk HTTP downloader, BitTorrent/Magnet support, resilient playlists, Chrome/Edge Manifest V3 extension, and Clipboard Watcher.
* **OmniDrop:** Zero-app LAN / Hotspot wireless transfer via QR code with Security PIN protection, client access control, shared clipboard history, and on-the-fly folder ZIP streaming.
* **Data & Media Utilities:** CSV Cleaner, Batch Renamer, CSV/Folder Splitter, Media Compressor (Canvas + FFmpeg), Media & Document Converter, Metadata Editor (`.mp3`, `.flac`, `.m4a`, `.wav`, `.ogg`), and SHA-256 Duplicate Finder.
* **Workspace Profiles:** Clean **Pro Core Suite** default or **Full Personal Suite** unlocking optional utilities (`Toolbox`, `Internet Radio`, `Live Television`, experimental `CineMatch`).

---

## Linux Prerequisites (Debian / Ubuntu / Mint / Pop!_OS)

```bash
sudo apt update && sudo apt install ffmpeg libnss3 libatk1.0-0 libasound2 -y
```

*(Arch: `sudo pacman -S ffmpeg nss atk alsa-lib` &bull; Fedora: `sudo dnf install ffmpeg nss atk alsa-lib`)*

*(Optional for Converter Document conversions `PDF`/`DOCX`/`ODT` only: `pip install pypandoc pdf2docx docx2pdf`.)*

---

## Third-Party Notices & Feedback

* Open-source engine attributions and licenses are listed in [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md).
* Found a bug or want to request a feature? Open an issue in the **Issues** tab.
