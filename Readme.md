# 🚀 EightBitAI v1.0.0 - Desktop AI Assistant & Search Overlay

We are excited to launch **EightBitAI**, a lightweight, transparent, floating pill-shaped search overlay designed to put powerful AI assistance, real-time voice dictation, and native desktop snipping right at your fingertips.

---

## ✨ Key Features in this Release

### 🔍 Minimalist Pill Interface & Dynamic Resizing
* Borderless, frameless, and transparent window pinned on top of your workspace (`Alt+Shift+S` and `Alt+Shift+D` global shortcuts).
* Programmatically resizes from a collapsed `110px` pill height to `580px` when active—ensuring transparent regions never block your standard OS mouse clicks.

### 🎤 Real-Time Voice Dictation
* Built-in browser-native WebSocket audio streaming powered by the **Deepgram Nova-2** engine.
* Transcripts populate the query input field *in real time* as you speak, complete with a pulsing visual soundwave track.

### 📸 Native Desktop Snipping & Vision AI
* Snap screenshots of your active display natively (`desktopCapturer`).
* Seamlessly integrates with the **Gemini** & **Llama 4 Scout** multimodal vision models to explain, describe, or troubleshoot whatever is on your screen.

### 🤖 Deep Research Scraper Loop
* AI Ask Mode spawns an intelligent research loop using Groq SDK.
* Performs initial searches, decides dynamically to scrape page contents (cleaning layout noise natively), executes secondary search queries, and streams a final synthesized markdown report with inline progress checks and citations.

### 🔒 Privacy-First Configuration
* Settings and API keys (Groq & Deepgram) are saved locally in the browser's `localStorage` sandbox and are never sent to external servers.

---

## 📦 Installer Packages & OS Compatibility

This release has been compiled for Windows, macOS, and Linux:

* **Windows**: `EightBitAI-win-x64.exe` (NSIS Easy Installer)
* **macOS (Apple Silicon)**: `EightBitAI-mac-arm64.dmg` (M1/M2/M3 native)
* **macOS (Intel Core)**: `EightBitAI-mac-x64.dmg`
* **Linux (Universal)**: `EightBitAI-linux-x64.AppImage` (runs on all distros)
* **Linux (Debian/Ubuntu)**: `EightBitAI-linux-x64.deb`

---

## 🛠️ How to Install

### 🪟 Windows
1. Download `EightBitAI-win-x64.exe`.
2. Run the installer and choose your installation options. It will automatically create desktop and start menu shortcuts.

### 🍎 macOS
1. Download the `.dmg` matching your architecture (`arm64` for Apple Silicon M-series, `x64` for Intel).
2. Open the `.dmg` and drag **EightBitAI** into your **Applications** folder.

### 🐧 Linux
* **AppImage**: Download `EightBitAI-linux-x64.AppImage`, right-click -> Properties -> Permissions -> Check "Allow executing file as program", and run it.
* **Debian/Ubuntu**: Download `EightBitAI-linux-x64.deb` and install via `sudo dpkg -i EightBitAI-linux-x64.deb` or double-click to install via Software Center.
