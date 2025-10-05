# 📝 Quick Notes — Chrome Extension  
_A lightweight, distraction-free note-taking extension built with React, TailwindCSS, and the Chrome Storage API._

![React](https://img.shields.io/badge/React-18.0-blue?logo=react)
![Tailwind](https://img.shields.io/badge/TailwindCSS-3.0-06B6D4?logo=tailwindcss)
![License](https://img.shields.io/badge/License-MIT-green)
![Manifest](https://img.shields.io/badge/Manifest-V3-orange)

---

## 🌟 Overview
**Quick Notes** is a minimal Chrome/Brave extension that lets you jot down thoughts directly from your browser toolbar.  
Your notes are stored locally using the **Chrome Storage API**, ensuring persistence even after you close or restart your browser.  

Simple. Fast. Private. 💡  

---

## 🎯 Features

| Feature | Description |
|----------|--------------|
| 📝 **Add Notes** | Quickly add short notes through the popup UI |
| 📄 **View Notes** | Display a scrollable list of saved notes |
| ❌ **Delete Notes** | Remove notes you no longer need |
| 💾 **Persistent Storage** | Notes are saved via `chrome.storage.local` |
| 🌙 **Dark Mode (optional)** | Toggle between light and dark themes |
| 📋 **Copy to Clipboard (optional)** | Copy a note’s text instantly |

---

## 🧱 Tech Stack

| Component | Technology |
|------------|-------------|
| Framework | [React](https://react.dev/) (via [Vite](https://vitejs.dev/)) |
| Styling | [TailwindCSS](https://tailwindcss.com/) |
| Storage | [Chrome Storage API](https://developer.chrome.com/docs/extensions/reference/storage) |
| Manifest | Manifest V3 |
| Icons | PNGs (16×16, 48×48, 128×128) |
| Supported Browsers | Chrome, Brave, Edge (Chromium-based) |

---

## 🗂️ Project Structure
```bash
quick-notes-extension/
│
├── public/
│   ├── icons/
│   │   ├── icon16.png
│   │   ├── icon48.png
│   │   └── icon128.png
│   └── manifest.json
│
├── src/
│   ├── App.jsx           # Main popup UI
│   ├── NoteItem.jsx      # Reusable note component
│   ├── storage.js        # Chrome storage helper
│   ├── main.jsx          # React entry file
│   └── index.css         # Tailwind styles
│
├── vite.config.js
└── package.json
