# 🤠 Red Dead Online Event Overlay
> **Never miss a Trade Route or Condor Egg again with professional, automated notifications.**

![Version](https://img.shields.io/badge/version-1.0.0-blueviolet?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-OBS%20|%20Streamer.bot-orange?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

This is a professional, real-time overlay designed specifically for Red Dead Online streamers. It features a globally synced UTC schedule, custom RDR-style typography, and deep Streamer.bot integration to keep you and your chat informed.

---

## ✨ Features
* 🌍 **Global UTC Sync:** Zero manual setup. Whether you're in PST, EST, or GMT, the schedule stays 100% accurate without Daylight Savings headaches.
* 🔔 **Auto-Notifications:** A notification "toast" slides in exactly 10 minutes before every event.
* 💬 **Chat Commands:** Full integration for `!fme` for the next event or specific event lookups (e.g., `!trade route` or `!tr`, `!King of the castle` or `!kotc`, `!fools gold` or `!fg` ect).
* 🎨 **RDR Aesthetic:** Matches the RDO interface with high-quality icons and game-accurate fonts.
* 🔊 **Audio Alerts:** Built-in spatial sound notification with customizable volume.

---

## 📸 Preview
*(Replace the image below with a real screenshot of your overlay once uploaded!)*
![Overlay Preview](preview.png)

---

## 📂 Folder Structure
For the code to find your assets correctly, your repository **must** follow this exact structure:

```text
/ (Root)
├── index.html              # The main overlay code
├── fme.wav                 # The notification sound
├── images/
│   └── toast_bg.png        # Background UI graphic
├── fonts/
│   ├── RDRLino-Regular.ttf
│   └── HapnaSlabSerif-Medium.ttf
└── fme/
    ├── fme_trade_route.png
    ├── fme_condor_egg.png
    └── (All other event icons...)