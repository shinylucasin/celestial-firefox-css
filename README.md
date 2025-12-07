# Tenshi Fox CSS - celestial-firefox-css

**[🇧🇷 Leia em Português](README-ptbr.md)**

A minimalist CSS "rice" for Firefox, focused on a dark theme with neon pink accents, inspired by the aesthetics of Tenshi Hinanawi (Touhou Project).

The goal is to clean up the interface, center elements, and give a "gamer/hacker" touch to the address bar without sacrificing performance.

## 🎨 Screenshots

![Tela Inicial](screenshots/firefox.png)

![Barra de Endereços](screenshots/barra_pesquisa.png)

## ✨ Features

* **Custom Address Bar:** "Dark mode" background (deep purple) with vibrant neon pink text and icons.
* **Centered Tabs:** Tab text is always centered for a cleaner look.
* **Auto-hiding Bookmarks:** The bookmarks bar remains hidden and only appears when hovering nearby (saving vertical space).
* **Audio Glow:** Tabs playing audio get a neon pink glow.
* **Clean Look:** Hidden 'X' (close) button on inactive tabs.

## 🚀 How to Install

To use this theme, you need to enable external CSS loading in Firefox.

### Step 1: Enable Customization
1.  Open Firefox and type `about:config` in the address bar. Accept the risk.
2.  Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
3.  Set the value to **`true`**.

### Step 2: Install the File
1.  Go to **Menu** > **Help** > **More Troubleshooting Information**.
2.  Find "Profile Folder" and click **Open Folder**.
3.  Create a folder named `chrome` inside it.
4.  Download the `userChrome.css` file from this repo and place it inside the `chrome` folder.
5.  **Restart Firefox.**

## ⚙️ Extra Settings (Optional)

* **Hardware Acceleration:** To ensure animations run smoothly, make sure hardware acceleration is forced in `about:config` (set `layers.acceleration.force-enabled` to `true`).
* **Firefox Color:** This CSS works great on its own, but you can use the official Firefox Color extension to tweak other theme details if you want to fully match your setup.

---

## ⚖️ Legal & License

**Copyright © 2025 - shinylucasin**

<details>
<summary>📄 <b>Click to view MIT License Summary</b></summary>

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software...
>
> **You can:** Use, copy, modify, merge, publish.
> **You must:** Include the original copyright notice.
> **Warranty:** None. The software is provided "as is".

[See full LICENSE file](LICENSE)
</details>

<p align="center">
  <i>Created with ❤️ and CSS by <a href="https://github.com/shinylucasin">shinylucasin</a></i>
</p>
