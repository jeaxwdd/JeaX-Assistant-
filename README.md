# JeaX-Assistant-
🎙️ Real-time voice AI assistant powered by the Gemini Live API. It hears, sees, talks, and controls your computer. Drop-in plugin system to teach it new skills with a single file

✨ Full Feature List
🎙️ Voice & Audio
Real-time voice conversation — ultra-low latency native audio streaming via Gemini Live API
Wake-word mode ("Hey JeaX") — local on-device detection, audio stays private before the wake phrase
Push-to-talk — global Alt+E hotkey (Windows) to open the mic only while held
Microphone & speaker picker — select exact input/output devices; auto-fallback if disconnected
Microphone gain control — 1x–8x digital gain for quiet mics, safely clipped
Discord / Call Mode — hears the other person on a call, answers real questions, stays silent on chatter, ignores its own voice
Affective dialog — detects emotion in your voice (tired, excited, frustrated) and adapts tone
Proactive audio — knows when you're NOT talking to it (room chatter, TV, phone calls) and stays silent
Unlimited session length — sliding-window context compression + session resumption; hours-long conversations
Auto language detection — adapts to your language from first use (Turkish, English, etc.)


👁️ Vision & Computer Control
Live screen streaming — continuous screen understanding for step-by-step PC operation
Screen & webcam analysis — vision piped directly into the Live session
Desktop operator — clicks, types, drags, scrolls, presses keys; verifies every step on-screen before claiming success
Browser control — open URLs, switch tabs, navigate by voice
App launcher — open any installed application by voice
System settings control — volume, brightness, WiFi, power actions (shutdown/restart gated by confirmation)
Face identification & forensics panel — 478-point MediaPipe face mesh, 3D head pose (yaw/pitch/roll), FACS action units (smile, blink, brow raise), EAR/MAR metrics, 128-D SFace identity matching, live enrollment and auto re-scan
Hand/gesture tracking (hologram hand) — MediaPipe-based hand tracking overlay


🧠 Memory & Intelligence
Persistent long-term memory — remembers projects, preferences and personal context across sessions
Session memory — summarizes each conversation, naturally mentions it next morning
Proactive check-ins 2.0 — time-aware, context-aware check-ins based on time of day and your projects
Morning briefing — greeting + time + yesterday recap + live news on first boot
Background topic monitoring — watches chosen topics daily and alerts naturally
🧩 Plugin System (the headline feature)
Drop-in plugins — put one .py file into plugins/, restart, the skill is live by voice in any language
Plugin Manager UI — per-plugin persistent ON/OFF toggles, status display
Crash isolation — a broken plugin can never take JeaX down; it shows as "BROKEN" with the error, everything else keeps running
Name collision detection — plugin/core tool conflicts rejected automatically
Plugin template — plugins/_template.py, fill in PLUGIN dict + run() and you're done


🔍 Search & Information
Multi-mode web search — news / research / price / compare / search; Gemini Grounding first, DuckDuckGo fallback
Live weather — for any city, personalized from memory
Flight finder — live flight prices and availability
YouTube control — search, play, pause, seek by voice
File processor — read, summarize, Q&A on local files
Screen processor — asks questions about what's currently on your screen


🛠️ Productivity
Smart reminders — OS-native scheduled notifications (Task Scheduler / LaunchAgent / systemd)
Task board — add, prioritize, complete, reopen tasks by voice or UI
Code helper — generate, edit, debug, run code; keeps .jeax.bak backups
Dev agent — builds entire standalone projects autonomously
Clipboard intelligence — copy any text → floating panel with Translate / Summarize / Explain / Fix
Chat takeover — monitors visible chat and replies in your style until you stop it


💬 Communication
Send messages — WhatsApp, Telegram, Discord (approval-gated for safety)
WhatsApp gateway — text JeaX from your phone; it replies through the gateway
Discord auto-typing — sends written Discord messages via Quick Switcher, verifying the conversation window first
Remote dashboard — control JeaX from your phone via QR-code pairing (FastAPI web panel with login)


🎮 Extras & Fun
Game updater — installs/updates Steam & Epic games, tracks downloads, schedules updates
Free game deals — Epic promotions, giveaways, F2P games with images
Aircraft radar — live flight radar on a map
Mini games & Roblox integration — voice-controlled gameplay
Push-up counter — webcam-based exercise counter
QR code generator


🖥️ System & Safety
Hardware monitoring — continuous CPU/RAM/GPU/temperature telemetry with spoken localized alerts
Dynamic Island — macOS-style media widget reading Spotify/YouTube metadata (SMTC)
Auto-start on boot — registry / LaunchAgent / .desktop registration
Security guard — debugger detection, core file integrity verification, config ACL tightening on startup
Confirmation gate — sensitive actions (sending messages, file deletion, shutdown, code execution, dependency installs) always require visible in-UI approval — muting the mic does not bypass it
IPv4-first networking — automatic DNS patching for reliable Google/YouTube connectivity
Cross-platform — Windows / macOS / Linux
