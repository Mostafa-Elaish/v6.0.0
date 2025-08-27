# Jarvis v6 - Smart Security System

**Jarvis v6** is a Raspberry Pi–powered smart security system with touchscreen control, Telegram alerts, camera-based surveillance, and full event logging.

## 🔧 Features

- 📷 Motion detection with camera snapshots and short video clips
- 📱 Telegram alerts (customizable video length, default 5s)
- 🧠 Touchscreen interface
- 🗂️ Log viewer with search, filtering, and bulk clearing (PIN-protected)
- 🧹 Auto media cleanup every day at 3 AM
- 🗓️ Configurable media retention (default: 30 days)
- 🔐 Master PIN required for critical actions
- ⚙️ Optional: System Health dashboard (CPU, disk, uptime, etc.)

## 📁 Folder Structure

jarvis-v6/
├── main.py # Main program
├── config.ini # Configuration file
├── logs/ # Event logs (auto-generated)
├── media/ # Camera snapshots and video clips
├── assets/ # Icons, UI assets (optional)
└── README.md # Project documentation
