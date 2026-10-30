<div align="center">
  
  <!-- Logo veya Başlık için Neon/Cyberpunk Stil -->
  <h1><span style="font-family: 'Courier New', Courier, monospace; font-weight: 800; letter-spacing: 2px; color: #00ffcc;">⚡ JeaX-Assistant ⚡</span></h1>
  
  <p><em><b>🎙️ Real-time voice AI assistant powered by the Gemini Live API</b></em></p>
  
  <p><b>Hears, sees, talks, and controls your computer with a drop-in plugin system.</b> 🚀</p>

  <br>

  <!-- Örnek Rozetler (Badges) -->
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Gemini-Live%20API-orange?style=for-the-badge&logo=google&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/Platform-Win%20%7C%20Mac%20%7C%20Linux-lightgrey?style=for-the-badge" alt="Platforms">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">

</div>

---

## <div align="center">✨ Full Feature List ✨</div>

### 🎙️ Voice & Audio
* **Real-time voice conversation** — Ultra-low latency native audio streaming via Gemini Live API 🔊
* **Wake-word mode (`"Hey JeaX"`)** — Local on-device detection, audio stays private before the wake phrase 🤫
* **Push-to-talk** — Global `Alt+E` hotkey (Windows) to open the mic only while held 🎙️
* **Microphone & speaker picker** — Select exact input/output devices; auto-fallback if disconnected 🎧
* **Microphone gain control** — `1x–8x` digital gain for quiet mics, safely clipped 🎚️
* **Discord / Call Mode** — Hears the other person on a call, answers real questions, stays silent on chatter, ignores its own voice 📞
* **Affective dialog** — Detects emotion in your voice (tired, excited, frustrated) and adapts tone 🎭
* **Proactive audio** — Knows when you're **NOT** talking to it (room chatter, TV, phone calls) and stays silent 🛑
* **Unlimited session length** — Sliding-window context compression + session resumption; hours-long conversations ⏳
* **Auto language detection** — Adapts to your language from first use (Turkish, English, etc.) 🌍

---

### 👁️ Vision & Computer Control
* **Live screen streaming** — Continuous screen understanding for step-by-step PC operation 🖥️
* **Screen & webcam analysis** — Vision piped directly into the Live session 👁️
* **Desktop operator** — Clicks, types, drags, scrolls, presses keys; verifies every step on-screen before claiming success 🖱️
* **Browser control** — Open URLs, switch tabs, navigate by voice 🌐
* **App launcher** — Open any installed application by voice 🚀
* **System settings control** — Volume, brightness, WiFi, power actions (shutdown/restart gated by confirmation) ⚙️
* **Face identification & forensics panel** — 478-point MediaPipe face mesh, 3D head pose (`yaw/pitch/roll`), FACS action units (smile, blink, brow raise), EAR/MAR metrics, 128-D SFace identity matching, live enrollment and auto re-scan 🧬
* **Hand/gesture tracking (hologram hand)** — MediaPipe-based hand tracking overlay ✋

---

### 🧠 Memory & Intelligence
* **Persistent long-term memory** — Remembers projects, preferences and personal context across sessions 🧠
* **Session memory** — Summarizes each conversation, naturally mentions it next morning ☀️
* **Proactive check-ins 2.0** — Time-aware, context-aware check-ins based on time of day and your projects ⏰
* **Morning briefing** — Greeting + time + yesterday recap + live news on first boot 🌅
* **Background topic monitoring** — Watches chosen topics daily and alerts naturally 📰

---

### 🧩 Plugin System <small style="color: #ffaa00;">(The Headline Feature)</small>
* **Drop-in plugins** — Put one `.py` file into `plugins/`, restart, the skill is live by voice in any language 🔌
* **Plugin Manager UI** — Per-plugin persistent ON/OFF toggles, status display 🎛️
* **Crash isolation** — A broken plugin can never take JeaX down; it shows as `"BROKEN"` with the error, everything else keeps running 🛡️
* **Name collision detection** — Plugin/core tool conflicts rejected automatically ⚠️
* **Plugin template** — `plugins/_template.py`, fill in `PLUGIN` dict + `run()` and you're done 📝

---

### 🔍 Search & Information
* **Multi-mode web search** — News / research / price / compare / search; Gemini Grounding first, DuckDuckGo fallback 🔍
* **Live weather** — For any city, personalized from memory 🌤️
* **Flight finder** — Live flight prices and availability ✈️
* **YouTube control** — Search, play, pause, seek by voice 📺
* **File processor** — Read, summarize, Q&A on local files 📂
* **Screen processor** — Asks questions about what's currently on your screen 🖥️

---

### 🛠️ Productivity
* **Smart reminders** — OS-native scheduled notifications (`Task Scheduler` / `LaunchAgent` / `systemd`) 🔔
* **Task board** — Add, prioritize, complete, reopen tasks by voice or UI 📋
* **Code helper** — Generate, edit, debug, run code; keeps `.jeax.bak` backups 💻
* **Dev agent** — Builds entire standalone projects autonomously 🛠️
* **Clipboard intelligence** — Copy any text ➔ floating panel with Translate / Summarize / Explain / Fix 📋
* **Chat takeover** — Monitors visible chat and replies in your style until you stop it 💬

---

### 💬 Communication
* **Send messages** — WhatsApp, Telegram, Discord (approval-gated for safety) 📤
* **WhatsApp gateway** — Text JeaX from your phone; it replies through the gateway 📱
* **Discord auto-typing** — Sends written Discord messages via Quick Switcher, verifying the conversation window first 💬
* **Remote dashboard** — Control JeaX from your phone via QR-code pairing (FastAPI web panel with login) 🌐

---

### 🎮 Extras & Fun
* **Game updater** — Installs/updates Steam & Epic games, tracks downloads, schedules updates 🎮
* **Free game deals** — Epic promotions, giveaways, F2P games with images 🎁
* **Aircraft radar** — Live flight radar on a map ✈️
* **Mini games & Roblox integration** — Voice-controlled gameplay 🕹️
* **Push-up counter** — Webcam-based exercise counter 🏋️‍♂️
* **QR code generator** — Quick code creation 🔲

---

### 🖥️ System & Safety
* **Hardware monitoring** — Continuous CPU/RAM/GPU/temperature telemetry with spoken localized alerts 📊
* **Dynamic Island** — macOS-style media widget reading Spotify/YouTube metadata (SMTC) 🏝️
* **Auto-start on boot** — Registry / LaunchAgent / `.desktop` registration 🚀
* **Security guard** — Debugger detection, core file integrity verification, config ACL tightening on startup 🔒
* **Confirmation gate** — Sensitive actions (sending messages, file deletion, shutdown, code execution, dependency installs) always require visible in-UI approval — muting the mic does not bypass it 🛑
* **IPv4-first networking** — Automatic DNS patching for reliable Google/YouTube connectivity 🌐
* **Cross-platform** — Windows / macOS / Linux 💻🐧🍏
