# telegram-bundle-bots
contact admin : https://t.me/miwheremi
# 🤖 Smart Token Bot v6.1 — Enhanced Edition

A fully automated, persistent, and production-ready **Telegram Token Creation Bot**.  
Built for Binance Smart Chain (BSC) with **watcher tracking**, **queue scheduling**, **COOK cloning**, and **auto-sell orchestration**.

---

## 🚀 Key Highlights

✅ **COOK Mode (Clone Existing Tokens)**  
✅ **Auto-Trigger Buy System** (based on wallet activity)  
✅ **Sequential Queue Engine** with profit continuity  
✅ **Watcher Tracking & Live Analytics**  
✅ **Persistent Menus + State Recovery**  
✅ **Custom Delay, Manual, or Instant Auto-Sell**  
✅ **Full History Export (CSV)**  
✅ **Per-User Data Isolation**  
✅ **Graceful Shutdown & Resume**  
✅ **Four.meme Token Metadata Fetching**  

---

## 🧩 Architecture Overview


📂 smart-token-bot/
├── smart-bot-final-v6.1-ENHANCED.js # Main runtime script
├── package.json # Node dependencies
├── .env # Environment configuration
├── /data/
│ ├── /users/ # Individual user folders
│ │ └── <chatId>/
│ │ ├── history.json
│ │ ├── templates.json
│ │ ├── schedules.json
│ │ ├── watcherInfo.json
│ │ └── logs.txt
│ ├── /temp/ # Temporary session files
│ └── ...
└── /modules/
├── messageManager.js # Telegram message handler
├── scheduler.js # Queue + timing management
├── watchers.js # Wallet watcher logic
├── storage.js # User data persistence
├── helpers.js # Formatting, utilities, etc.
