<div align="center">

<img src="https://himworks.github.io/TriBite/favicon.png" width="120" height="120" alt="TriBite Logo" style="image-rendering: pixelated;">

# TriBite

### Calculate. Play. Write. Ask.

**A lightweight all-in-one Progressive Web App built by [HIMworks](https://github.com/HIMworks).**

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-3B9DFF?style=for-the-badge&logo=githubpages&logoColor=white)](https://himworks.github.io/TriBite/)
[![License](https://img.shields.io/badge/License-MIT-ffcf56?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Ready-5fd4c7?style=for-the-badge&logo=pwa&logoColor=white)](https://himworks.github.io/TriBite/)

[![Stars](https://img.shields.io/github/stars/HIMworks/TriBite?style=flat-square&logo=github&color=ffcf56)](https://github.com/HIMworks/TriBite/stargazers)
[![Forks](https://img.shields.io/github/forks/HIMworks/TriBite?style=flat-square&logo=github&color=3B9DFF)](https://github.com/HIMworks/TriBite/network/members)
[![Issues](https://img.shields.io/github/issues/HIMworks/TriBite?style=flat-square&logo=github&color=ff6b6b)](https://github.com/HIMworks/TriBite/issues)
[![Last Commit](https://img.shields.io/github/last-commit/HIMworks/TriBite?style=flat-square&logo=git&color=5fd4c7)](https://github.com/HIMworks/TriBite/commits/main)

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Why TriBite?](#-why-tribite)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Progressive Web App](#-progressive-web-app)
- [Roadmap](#-roadmap)
- [Future Plans](#-future-plans)
- [Folder Structure](#-folder-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🎯 About

**TriBite** is a fast, lightweight, and installable all-in-one web application that combines productivity, entertainment, and AI assistance into a single seamless experience. Built with vanilla JavaScript and modern web standards, TriBite requires zero backend — everything runs entirely in your browser with data persisted via `localStorage`.

Whether you need to crunch numbers, jot down ideas with sketches, chat with an AI assistant, or kill time with a pixel-art endless runner — TriBite has you covered.

> 🌐 **Live Demo:** [https://himworks.github.io/TriBite/](https://himworks.github.io/TriBite/)

---

## ✨ Features

| Module | Description | Key Capabilities |
|--------|-------------|------------------|
| 🧮 **Calculate It** | Advanced scientific calculator with expression evaluation | • Real-time expression parsing <br>• Trigonometry (sin, cos, tan) with DEG/RAD toggle <br>• Logarithms, roots, factorial, constants (π, e) <br>• Polynomial solver (Linear, Quadratic, Cubic) with step-by-step working <br>• Unit converter (Length, Mass, Temperature, Volume, Speed) <br>• Calculation history with recall |
| 📝 **Notes** | Full-featured note-taking with rich text & drawing | • Rich text formatting (bold, italic, underline, color, size) <br>• Freehand sketching with brush sizes & colors <br>• Folder organization with tabbed navigation <br>• Full-text search across all notes <br>• Pin/star important notes <br>• Image attachments <br>• Export to PDF (text + sketches) |
| 🤖 **biteAI** | AI-powered assistant with streaming support | • Natural language Q&A via Mistral Large <br>• Streaming responses for real-time feel <br>• Regenerate, stop, and copy responses <br>• Persistent chat history per account <br>• Markdown rendering (code blocks, lists, bold, headers) <br>• Clear conversation with confirmation |
| 🎮 **Play** | Pixel-art endless runner with progression | • 3-lane dodging with jump mechanics <br>• Coin collection & scoring system <br>• **TURN!** mechanic — swipe the correct direction when prompted <br>• Level progression (Lv. 1–∞) <br>• Achievement system with unlockable badges <br>• Theme shop (Sunset, Ocean, Forest) <br>• Skin shop (Classic, Crimson, Neon, Gold) <br>• Collectible crystals & blooms <br>• Keyboard, touch, and swipe controls |
| ⚙️ **Settings** | Per-account customization & data management | • 3 independent user accounts with PIN locks <br>• Custom avatars (image upload) <br>• Account renaming <br>• Dark / Light / System theme + Cosmic mode <br>• Edge-swipe drawer navigation <br>• Per-account data isolation <br>• Full account reset capability |

---

## 📸 Screenshots

<div align="center">

| Landing Page | Home (Light Theme) | Home (Dark Theme) |
|:------------:|:------------------:|:-----------------:|
| <img src="screenshots/landing-page.png" width="260" alt="Landing Page"> | <img src="screenshots/home-light.png" width="260" alt="Home Light"> | <img src="screenshots/home-dark.png" width="260" alt="Home Dark"> |

| Calculator | Notes Editor | Math Lab |
|:----------:|:------------:|:--------:|
| <img src="screenshots/calculator.png" width="260" alt="Calculator"> | <img src="screenshots/notes.png" width="260" alt="Notes"> | <img src="screenshots/mathlab.png" width="260" alt="Math Lab"> |

| biteAI Chat | Pixel Runner Game |
|:-----------:|:-----------------:|
| <img src="screenshots/biteai.png" width="260" alt="biteAI"> | <img src="screenshots/game.png" width="260" alt="Game"> |

</div>

---

## 💡 Why TriBite?

| Criteria | TriBite | Typical Web Apps |
|----------|---------|------------------|
| **Privacy** | ✅ Zero backend — all data stays on your device | ❌ Often requires server-side storage |
| **Offline** | ✅ Full PWA — works without internet | ❌ Requires constant connectivity |
| **Installable** | ✅ Add to Home Screen on any platform | ❌ Browser-only experience |
| **Accounts** | ✅ 3 isolated profiles with PIN protection | ❌ Single-user or login-required |
| **Bundle Size** | ✅ Single HTML file, zero dependencies (except jsPDF) | ❌ Heavy frameworks, large bundles |
| **Performance** | ✅ Instant load, 60fps game, smooth animations | ❌ Loading spinners, janky transitions |
| **AI Included** | ✅ Built-in AI assistant (no API key needed) | ❌ Requires external setup or paid keys |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square) | Semantic markup & structure |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square) | Custom properties, animations, responsive design |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square) | Vanilla ES6+ — zero frameworks |
| ![PWA](https://img.shields.io/badge/Progressive_Web_App-5A0FC8?logo=pwa&logoColor=white&style=flat-square) | Service Worker, Web App Manifest, offline support |
| ![jsPDF](https://img.shields.io/badge/jsPDF-000000?logo=adobe&logoColor=white&style=flat-square) | Client-side PDF generation for notes export |
| ![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white&style=flat-square) | Lightweight AI proxy for biteAI |

---

## 🚀 Installation

### Option 1: Visit the Website (Recommended)
Simply open [**https://himworks.github.io/TriBite/**](https://himworks.github.io/TriBite/) in any modern browser. No installation required.

### Option 2: Install as PWA

#### On Desktop (Chrome/Edge)
1. Visit the live demo
2. Click the **➕ Install** icon in the address bar
3. TriBite launches as a standalone desktop app

#### On Android (Chrome)
1. Visit the live demo
2. Tap **⋮ Menu → Add to Home screen**
3. Confirm installation

#### On iOS (Safari)
1. Visit the live demo
2. Tap **Share → Add to Home Screen**
3. TriBite appears as a native app icon

### Option 3: Self-Host / Develop Locally
```bash
# Clone the repository
git clone https://github.com/HIMworks/TriBite.git

# Navigate into the project
cd TriBite

# Serve with any static file server
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# Or simply open index.html in your browser
```

---

## 📱 Progressive Web App

TriBite is built as a first-class PWA:

| Feature | Status | Description |
|---------|--------|-------------|
| **Web App Manifest** | ✅ | `manifest.json` with icons, theme colors, and display modes |
| **Service Worker** | ✅ | `sw.js` enables offline caching and fast repeat visits |
| **Install Prompt** | ✅ | Browser-native install on desktop & mobile |
| **Standalone Mode** | ✅ | Launches without browser chrome (fullscreen app feel) |
| **Theme Color** | ✅ | Dynamic meta `theme-color` adapts to selected theme |
| **Responsive** | ✅ | Optimized for mobile (320px+) through desktop |
| **Touch Gestures** | ✅ | Edge-swipe drawer, tap targets ≥ 42px, haptic-friendly |

---

## 🗺️ Roadmap

- [x] Core calculator with history
- [x] Polynomial solver with step-by-step working
- [x] Unit converter (Length, Mass, Temp, Volume, Speed)
- [x] Notes with rich text formatting
- [x] Drawing/sketching canvas in notes
- [x] Folder-based note organization
- [x] Full-text search
- [x] PDF export (text + drawings)
- [x] biteAI integration with streaming
- [x] Chat history persistence
- [x] Pixel-art endless runner game
- [x] Coin economy & shop system
- [x] Achievement system
- [x] Level progression
- [x] Multiple themes (Dark, Light, Cosmic, Sunset, Ocean, Forest)
- [x] Multi-account system with PIN locks
- [x] Custom avatars
- [x] PWA installability
- [x] Service Worker for offline use
- [x] Math Lab (precision arithmetic)
- [ ] Cloud sync option
- [ ] Export/import data backup
- [ ] Keyboard shortcuts reference
- [ ] Voice input for biteAI
- [ ] Game leaderboard (local)
- [ ] Custom themes via CSS upload
- [ ] Note templates
- [ ] Collaborative notes (WebRTC)

---

## 🔮 Future Plans

| Phase | Goal | ETA |
|-------|------|-----|
| **v1.5** | Math Lab module — high-precision arithmetic for very large numbers | Q3 2026 |
| **v1.6** | Data export/import (JSON backup & restore across devices) | Q3 2026 |
| **v1.7** | Voice input for biteAI & notes dictation | Q4 2026 |
| **v1.8** | Custom theme builder — upload your own CSS variables | Q4 2026 |
| **v2.0** | Optional cloud sync (end-to-end encrypted) | 2027 |

---

## 📁 Folder Structure

```
TriBite/
├── index.html              # Main application (single-file SPA)
├── favicon.png             # App icon (32×32, 192×192, 512×512)
├── manifest.json           # PWA manifest
├── sw.js                   # Service Worker for offline caching
├── screenshots/            # README & store screenshots
│   ├── landing-page.png
│   ├── home.png
│   ├── calculator.png
│   ├── notes.png
│   ├── biteai.png
│   ├── game.png
│   └── settings.png
├── LICENSE                 # MIT License
└── README.md               # This file
```

> **Note:** TriBite is intentionally built as a **single-file application** (`index.html`). All CSS, JavaScript, and HTML live in one file for maximum portability, zero build steps, and instant deployment.

---

## 🤝 Contributing

Contributions are welcome! TriBite is a community-driven project and we appreciate your help.

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

### Contribution Guidelines

- 🎨 Follow the existing pixel-art / retro aesthetic
- 📱 Ensure mobile-first responsiveness
- ⚡ Keep bundle size minimal — prefer vanilla JS
- 🔒 Maintain privacy-first architecture (no external data leaks)
- 🧪 Test across Chrome, Safari, Firefox, and Edge

### Reporting Issues

Found a bug or have a feature request? [Open an issue](https://github.com/HIMworks/TriBite/issues) and we'll look into it!

---

## 📄 License

```
MIT License

Copyright (c) 2026 HIMworks

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👤 Author

<div align="center">

**Made with ❤️ by [HIMworks](https://github.com/HIMworks)**

[![GitHub](https://img.shields.io/badge/GitHub-HIMworks-181717?style=flat-square&logo=github)](https://github.com/HIMworks)
[![Website](https://img.shields.io/badge/Website-TriBite-3B9DFF?style=flat-square&logo=githubpages)](https://himworks.github.io/TriBite/)

</div>

---

<div align="center">

⭐ **Star this repo if you find it useful!** ⭐

**[⬆ Back to Top](#-tribite)**

*© 2026 TriBite by HIMworks. All rights reserved.*

</div>
