# 🌌 Sumon Infinity — Personal Portfolio Website

> *"Building beyond boundaries — crafting digital experiences that transcend the ordinary."*

[![License: MIT](https://img.shields.io/badge/License-MIT-7B2FFF.svg)](LICENSE)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-181717?logo=github&logoColor=white)](https://pages.github.com/)

---

## ✨ Live Demo

🔗 **[https://sumon-infinity.github.io](https://sumon-infinity.github.io)**

---

## 📸 Preview

```
╔════════════════════════════════════╗
║  S∞   About  Services  Projects   ║
╠════════════════════════════════════╣
║                                    ║
║         SUMON                      ║
║         INFINITY                   ║
║                                    ║
║  Full-Stack Developer & AI Arch.   ║
║                                    ║
║  [View My Work]  [GitHub Profile]  ║
╚════════════════════════════════════╝
```

---

## 🚀 Features

- **Cosmic Dark Theme** — Deep space gradients, animated star field, glowing orb
- **Custom Cursor** — Smooth trailing cursor with hover effects
- **Animated Hero** — Staggered entrance animations with Orbitron typography
- **Skill Bars** — Scroll-triggered animated progress bars
- **Counter Animation** — Numbers count up when scrolled into view
- **GitHub Section** — Profile card, pinned repos, and live contribution heatmap
- **Contact Form** — Animated submit with success feedback
- **Scroll Reveal** — Elements fade in as you scroll
- **Fully Responsive** — Mobile-first, works on all screen sizes
- **Zero Dependencies** — Pure HTML, CSS, JavaScript. No frameworks needed.

---

## 📁 Project Structure

```
sumon-infinity/
├── index.html          # Main website (single file, fully self-contained)
├── README.md           # This file
├── LICENSE             # MIT License
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploy to GitHub Pages
```

---

## 🛠️ Getting Started

### Option 1 — Open Locally
```bash
# Clone the repo
git clone https://github.com/sumon-infinity/sumon-infinity.git

# Open in browser
open index.html
# or on Windows:
start index.html
```

### Option 2 — Deploy to GitHub Pages (Free Hosting)

See the [Deployment Guide](#-deployment-to-github-pages) below.

---

## 🌐 Deployment to GitHub Pages

### Step 1 — Create GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: `sumon-infinity` *(or your username for `username.github.io`)*
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Push Your Code
```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# First commit
git commit -m "🚀 Initial commit — Sumon Infinity portfolio"

# Add your GitHub repo as remote
git remote add origin https://github.com/YOUR_USERNAME/sumon-infinity.git

# Push to GitHub
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select: `Deploy from a branch`
4. Branch: `main` | Folder: `/ (root)`
5. Click **Save**
6. Wait ~2 minutes — your site will be live at:
   `https://YOUR_USERNAME.github.io/sumon-infinity`

### Step 4 — Auto Deploy (Optional)
The `.github/workflows/deploy.yml` file included in this repo will automatically redeploy your site every time you push to `main`. No manual steps needed after setup.

---

## ✏️ Customization Guide

### Change Your Name & Title
In `index.html`, find and update:
```html
<!-- Hero section -->
<span class="line1">SUMON</span>
<span class="line2">INFINITY</span>
<p class="hero-sub">Your tagline here...</p>
```

### Update Contact Links
```html
<a href="mailto:YOUR@EMAIL.com" class="contact-link ...">
<a href="https://github.com/YOUR_USERNAME" ...>
<a href="https://linkedin.com/in/YOUR_HANDLE" ...>
```

### Change Color Theme
All colors are CSS variables at the top of the `<style>` block:
```css
:root {
  --glow: #7B2FFF;    /* Primary purple glow */
  --accent: #00D4FF;  /* Cyan accent */
  --gold: #FFB800;    /* Gold highlight */
}
```

### Add Real Projects
Find the `#projects` section and replace the placeholder cards with your actual work.

### Connect GitHub Stats (Live Data)
Replace the static stats with [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) API calls or embed your actual GitHub contribution graph using the [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) project.

---

## 📦 Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (Variables, Grid, Animations, `clip-path`) |
| Interactivity | Vanilla JavaScript (ES6+) |
| Fonts | Orbitron, Syne, JetBrains Mono (Google Fonts) |
| Hosting | GitHub Pages |
| CI/CD | GitHub Actions |

---

## 📜 License

MIT License — free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Found a bug or want to improve something?

```bash
# Fork the repo, then:
git checkout -b feature/your-improvement
git commit -m "✨ Add your improvement"
git push origin feature/your-improvement
# Open a Pull Request
```

---

<div align="center">
  Built with 💜 by <strong>Sumon Infinity</strong> — reaching for the ∞
</div>
