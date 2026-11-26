<div align="center">

# 🌐 Marly's Dev Tools — Portfolio & Project Hub

**A modern, dynamic developer portfolio showcasing my Roblox tools, AI projects, and open-source releases.**

[![Live Website](https://img.shields.io/badge/Live_Website-gamesstudiomarly--design.github.io-22d3ee?style=for-the-badge&logo=github)](https://gamesstudiomarly-design.github.io/)
[![Made With](https://img.shields.io/badge/Made_with-HTML_%7C_CSS_%7C_JS-7c5cff?style=for-the-badge)](https://github.com/gamesstudiomarly-design/gamesstudiomarly-design.github.io)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)]()

</div>

---

## 🚀 Visit the Live Website

👉 **[https://gamesstudiomarly-design.github.io/](https://gamesstudiomarly-design.github.io/)**

---

## ✨ Features

This portfolio isn't just a static page — it uses the **GitHub REST API** to automatically stay up-to-date with my latest work.

### 1. 📦 Auto-Syncing GitHub Repositories
The "My Projects" grid automatically fetches my latest public repositories directly from GitHub. It displays:
- The repository name and description
- Live star and fork counts
- The primary programming language
*(Whenever I create a new repo or update an existing one, this site updates instantly without me touching the code).*

### 2. 🚀 Live Release Notes & Downloads
The "Latest Release" section pulls the newest release from my main project, **[ZeroScript 2.0](https://github.com/gamesstudiomarly-design/ZeroScript-2.0)**.
- Automatically displays the changelog.
- Creates dynamic, one-click download buttons for `.rar` and `.rbxmx` assets.
- Includes a fallback link to GitHub if the API hits a rate limit.

### 3. 🔒 Secure Admin Panel (Local)
The site includes a hidden Admin Dashboard to manage custom links, YouTube videos, or external projects.
- **Login:** Click the "🔒 Admin Login" button in the top right.
- **Credentials:** 
  - **Username:** `admin`
  - **Password:** `**************`
- **How it works:** Once logged in, the Admin Panel appears at the top. You can add custom projects (Title, Description, URL). These are saved to your browser's `localStorage`. When logged in, a red "✕" button appears on custom cards so you can delete them.

> ⚠️ **Note on Admin Data:** Because GitHub Pages is static (no database), projects added via the Admin Panel are saved *only in your specific browser*. If you visit the site on another device, those custom links won't appear. This is intended for previewing links before hardcoding them or sharing them locally.

### 4. 🎨 Modern Dark UI
- **Theme:** Dark gaming aesthetic with a purple (`#7c5cff`) and electric blue (`#22d3ee`) accent palette.
- **Responsive:** Fully functional on mobile, tablet, and desktop.
- **Animations:** Smooth hover effects, glowing gradients, and loading pulses.

---

## 🛠️ How This Was Built

This entire site is a **single-file `index.html`** containing HTML, CSS, and Vanilla JavaScript. No frameworks, no build steps, no NPM installs. It is served for free via **GitHub Pages**.

### Project Structure
