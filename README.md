# ⬇️ BestDownloader — Premiere Pro Panel

**Paste a link. Get the clip. Right inside Premiere.**
BestDownloader downloads videos and images from YouTube, Instagram, Pinterest, TikTok, Reddit, X and hundreds of other sites — into a queue, and straight into your Premiere Pro project.

### 🎁 Try it free for 14 days — no card, no sign-up

[![Download the free trial](https://img.shields.io/badge/⬇️_Download_free_trial-14_days_free-22C55E?style=for-the-badge)](../../releases/latest)

Install it, open it in Premiere and click **Start 14-day free trial**. Like it? Keep it for **₹499 once, lifetime** — [buy here](#-buy-a-license).

> 💰 This is a **paid tool**. The source code is private — this repo is the official showcase, changelog and support page.

---

## 😩 The Problem

You need a reference clip, a Pinterest moodboard or an Instagram Reel for your edit. So you open a sketchy downloader site, fight pop-up ads, download the file… and Premiere refuses to import it because it's VP9.

## ✅ The Fix

| Feature | What it means for you |
|---|---|
| 🌐 **Hundreds of sites** | YouTube, Instagram, Pinterest, TikTok, X, Reddit, Facebook, Vimeo, Twitch, Behance, Threads and more |
| 🖼️ **Videos *and* images** | Instagram carousels, Pinterest boards, image posts — not just videos |
| 🧩 **Browser extension, free** | Right-click any image, video or link in Chrome or Firefox → **Send to BestDownloader** → it's on your timeline |
| 📋 **Clipboard watching** | Copy a link anywhere on your computer — the panel offers to queue it in one click |
| 📥 **Bulk paste & queue** | Paste one link or thirty; duplicates removed, downloads run one by one with live progress |
| 🎞️ **Auto-import to Premiere** | Finished files land in the project bin you choose |
| 🔧 **Premiere-ready files** | VP9 / AV1 videos auto-converted to H.264 (or ProRes); webp/avif/heic images to PNG. Files that already work are never touched |
| 🎚️ **Format options** | Resolution cap, audio-only, subtitles, container choice |
| 🍪 **Instagram login, safely** | Reuses your browser session — no password typed into the panel |
| ✅ **Tested** | 50 automated tests covering routing, downloads, fallbacks and conversion |

---

## 💻 Requirements

- Adobe Premiere Pro **2021 (v15.0) or later**
- **macOS** or **Windows**
- Helper tools (yt-dlp, gallery-dl, ffmpeg) download themselves on first start, about 100 MB, once

---

## 🎬 Demo

*Demo video coming soon on [YouTube @androguruji](https://www.youtube.com/@androguruji).*

---

## ⬇️ Download & free trial

1. Download **`BestDownloader-<version>-Install.zip`** from the **[latest release](../../releases/latest)**.
2. Unzip it, then:
   - **Mac:** double-click `Install BestDownloader (Mac).command`
   - **Windows:** double-click `Install BestDownloader (Windows).bat` (if Windows warns: *More info → Run anyway*)
3. Restart Premiere Pro → **Window → Extensions → BestDownloader**.
4. Click **Start 14-day free trial**. No key needed to try it.

The panel tells you when a new version is out and updates itself.

## 🧩 Browser extension: Send to BestDownloader (free)

Found the perfect image on Google Images, a Pinterest pin or a reel while browsing? **Right-click it → Send to BestDownloader**, and it downloads straight into your Premiere project and onto the timeline. No copy-paste, no Downloads folder.

- **Right-click an image** → the full-size picture is saved (on Google Images it grabs the original, not the blurry thumbnail)
- **Right-click a video or a link** → it goes into the download queue
- **Click the toolbar button** → sends the page you're on (a YouTube video, a reel, a pin)
- Premiere must be open with the panel. Nothing is sent anywhere except to the panel on your own computer.

**Install it in Chrome, Edge or Brave (once, free):**
1. In the panel open **Settings → Browser extension → Chrome: show extension folder** (its path is copied for you).
2. In Chrome go to `chrome://extensions` and turn on **Developer mode** (top right).
3. Click **Load unpacked** and choose that folder. Done: right-click anything to try it.

**Install it in Firefox (once, free):**
1. In the panel open **Settings → Browser extension → Add to Firefox**.
2. Firefox opens and asks *"Add Send to BestDownloader?"* → click **Add**. Done.

## 🧪 Beta builds

Want new features first? In the panel open **Settings → Beta builds → Join the beta**. Beta versions then show up as updates. Something not right? Click **Leave the beta** and the panel puts the regular version back. Please [report beta bugs here](../../issues).

## 🛒 Buy a license

**Not sure yet? Try it free for 14 days first — no card, no sign-up.**

[![Download the free trial](https://img.shields.io/badge/⬇️_Download_free_trial-14_days_free-22C55E?style=for-the-badge)](../../releases/latest)

Then keep it for **₹499 once, lifetime.** No subscription. One key works on 2 computers.

[![Buy BestDownloader](https://img.shields.io/badge/🛒_Buy_BestDownloader-₹499_lifetime-7C3AED?style=for-the-badge)](https://superprofile.bio/vp/bestdownloader-%E2%80%93-stock-photos---videos-in-premiere-pro)

Your license key arrives by email right after the purchase.

---

## 🐞 Support

Found a bug or have a feature request? Open an **[Issue](../../issues)** in this repo.

---

## 📝 Changelog

Full notes for every version are on the **[Releases](../../releases)** page.

- **v1.26.11** — Stability: a cleaner, more robust release build
- **v1.26.11** — Cleaner release build: every panel file gets its own internal names
- **v1.26.10** — Browsers that aren't on the computer can't be picked for cookies; clearer cookie errors; updates keep one backup
- **v1.26.9** — Settings → Help: Report a bug (opens a GitHub issue with your versions filled in) and a panel log
- **v1.26.8** — Converting a 4K download no longer freezes the panel ("stuck on Moving files into place"); it shows a percentage and can be cancelled
- **v1.26.7** — gallery-dl installs on Windows
- **v1.26.6** — 14-day free trial; the Buy button always opens
- **v1.26.0** — License keys, team keys, and updates inside the panel
- **v1.20.0** — Multi-site downloads, image galleries, clipboard watching, auto Premiere-compatibility conversion

---

### ⚠️ Use responsibly

Downloading other people's content may break a platform's Terms of Service. Use BestDownloader for your own uploads, Creative Commons material, licensed footage, or content you have permission to use.

---

Made by **[Vikas Singh — Androguruji](https://github.com/androguruji1)** · Built with AI for editors 🎬🤖
