# 🚀 EightBitAI - Desktop AI Assistant & Search Overlay

Welcome to **EightBitAI**, a lightweight, transparent, floating pill-shaped search overlay designed to put powerful AI assistance, intelligent research agents, real-time voice dictation, and native desktop snipping right at your fingertips. 

Capable of handling both standard AI tasks and complex autonomous agent loops, EightBitAI leverages DuckDuckGo for highly accurate web searches without the noise.

🌐 **Visit at:** [https://eightbit-ai.vercel.app](https://eightbit-ai.vercel.app)

---

<img width="1492" height="942" alt="agent" src="https://github.com/user-attachments/assets/e7e20420-2ca1-4552-a898-5e3a98ddc260" />


## ✨ Key Features

### 🔍 Search & Research
* **Deep Web Research Agent:** Autonomous multi-step search loops scrape and synthesize clean, cited markdown reports—no ads, no distractions, no browser switching required. Powered by accurate web searches using DuckDuckGo.
* **Inline Image Discovery:** Agent-mode responses now surface relevant images found during web scraping, displaying them seamlessly in an intuitive, magazine-style gallery.

### 🧠 AI & Context
* **Multi-turn Chat Threads:** Context-preserving conversation threads let you ask follow-up questions naturally, keeping the AI focused on your ongoing workflow.
* **Multi-Provider Model Toggle:** Switch instantly between top-tier AI models, including Groq, Gemini, OpenAI, and Claude, to suit the specific task at hand.
* **Screen Capture & Vision AI:** Snap any region of your screen natively (`desktopCapturer`)—a terminal error, UI bug, or design mockup—and let multimodal models analyze it instantly without leaving your workflow.

### 💻 System Integration
* **Local File & Directory Access:** Read code files and explore folder trees directly in the overlay. The agent scans your workspace context automatically and intelligently filters out build artifacts and dependency directories.
* **Minimalist Pill Interface & Dynamic Resizing:** A borderless, frameless, and transparent window pinned on top of your workspace (`Alt+Shift+S` and `Alt+Shift+D` global shortcuts). It programmatically resizes from a collapsed `110px` pill to `580px` when active—ensuring transparent regions never block your standard OS mouse clicks.
* **Real-Time Voice Dictation:** Stream audio via browser-native WebSockets to the transcription engine. Transcripts populate the query input field *in real time* as you speak.

### 🔒 Privacy & Security
* **Encrypted API Key Storage:** API keys are strictly protected by Electron's `safeStorage` AES-256 keychain. Your credentials stay secure on your device and are never sent to external servers.

---

## 📦 Installer Packages & OS Compatibility

EightBitAI is compiled and fully supported across Windows, macOS, and Linux:

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
* **AppImage**: Download `EightBitAI-linux-x64.AppImage`, right-click -> **Properties** -> **Permissions** -> Check "Allow executing file as program", and run it.
* **Debian/Ubuntu**: Download `EightBitAI-linux-x64.deb` and install via your terminal with `sudo dpkg -i EightBitAI-linux-x64.deb` or double-click to install via your Software Center.
