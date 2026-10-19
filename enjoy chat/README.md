# EnjoyMessage — Project Files & Setup Guide

## 📁 Project Directory
**Path:** `C:\Users\hp\.gemini\antigravity\scratch\ghostchat\`

This project is built as a complete, **self-contained zero-dependency web app**. Everything (CSS, HTML, JavaScript, WebRTC P2P networking, notifications, and dark theme) is bundled cleanly inside **`index.html`** so you can run it without needing Node.js or complex server setups.

---

## 📄 File Inventory

1. [`index.html`](file:///C:/Users/hp/.gemini/antigravity/scratch/ghostchat/index.html)
   - **Type:** Single Page Application (HTML5 + CSS3 + Vanilla JavaScript + WebRTC)
   - **Size:** ~47 KB
   - **Includes:**
     - **Page 1: Notifications** (incoming connection alerts, timeout alerts, partner unique code display with one-click "Connect Back")
     - **Page 2: Permanent Private ID** (Google ID-style permanent unique handle, copy, custom edit, randomizer, standby listening)
     - **Page 3: Message Box** (Lobby with random 1-100 room pairing, direct alphanumeric code entry, P2P live chat, photo sharing up to 6 MB, typing indicator)
     - **Timer:** 60-second corner countdown timer with smooth SVG arc ring
     - **UI:** Pure dark-mode aesthetic with dark buttons and ambient starfield canvas

2. [`README.md`](file:///C:/Users/hp/.gemini/antigravity/scratch/ghostchat/README.md)
   - **Type:** Documentation & setup instructions

---

## 🚀 How to Run & Share

### Option 1: Run locally on your Desktop
Simply double click `index.html` or open it with your browser:
```text
file:///C:/Users/hp/.gemini/antigravity/scratch/ghostchat/index.html
```

### Option 2: Host for Free on the Web (to share online)
1. **GitHub Pages (Free)**:
   - Create a repository on GitHub (e.g. `enjoy-message`).
   - Upload `index.html`.
   - Go to **Settings > Pages** and select `main` branch.
   - Your site will be live at `https://<your-username>.github.io/enjoy-message/`.

2. **Netlify Drop (10 seconds, zero setup)**:
   - Go to [Netlify Drop](https://app.netlify.com/drop).
   - Drag and drop the `ghostchat` folder onto the page.
   - You get an instant `https://....netlify.app` public link to share with anyone.
