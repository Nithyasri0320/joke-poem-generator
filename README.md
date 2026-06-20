# 😂🖋️ JokePen – Joke Generator + Poem Writer

> A sleek AI-powered web app to generate jokes and write poems using Claude AI.

![JokePen Preview](https://img.shields.io/badge/Powered%20by-Claude%20AI-blueviolet?style=flat-square)
![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Features

### 😂 Joke Generator
- **7 categories** – Random, Tech & Coding, Science, Dad Jokes, Dark Humor, Puns, Office
- **4 styles** – One-liner, Q&A Setup, Story, Roast
- Custom topic/keyword support
- Session history (last 5 jokes)

### 🖋️ Poem Writer
- **6 poem types** – Free Verse, Haiku, Sonnet, Limerick, Ballad, Acrostic
- **6 moods** – Melancholic, Joyful, Romantic, Philosophical, Playful, Mysterious
- Custom theme input
- 3 length options
- Session history (last 5 poems)

### General
- One-click copy to clipboard
- Clean, responsive UI
- Zero dependencies – single HTML file

---

## 🚀 Quick Start

### Option 1: Open directly
Just open `index.html` in your browser. Done!

### Option 2: GitHub Pages
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Visit `https://yourusername.github.io/joke-poem-generator`

---

## 🛠️ How It Works

This app calls the **Anthropic Claude API** directly from the browser.

> **Note:** The API key is handled server-side by Claude.ai when run as an artifact. To deploy standalone, you'll need a backend proxy.

### Stack
- Pure HTML + CSS + Vanilla JS
- Anthropic Claude API (`claude-sonnet-4-6`)
- Google Fonts (Playfair Display, DM Sans, DM Mono)

---

## 📁 Project Structure

```
joke-poem-generator/
├── index.html    # Everything lives here
└── README.md     # You're reading this
```

---

## 🎨 Customization

Open `index.html` and tweak:
- `--rose` / `--violet` / `--gold` CSS variables → change accent colors
- Chip arrays in HTML → add more categories, moods, styles
- System prompts in JS → adjust the AI's tone

---

## 📄 License

MIT – use freely, credit appreciated.

---

Built with ❤️ using [Claude AI](https://www.anthropic.com)
