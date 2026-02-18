<h1 align="center">⚡ Chain Reaction ⚡</h1>

<p align="center">
  <i>An element-themed multiplayer strategy board game with immersive visuals & sound — built entirely with HTML, CSS & JavaScript.</i>
</p>

<p align="center">
  <a href="https://project-cs-3.vercel.app"><b>🎮 Play Now → project-cs-3.vercel.app</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-85.9%25-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-14.1%25-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Deployed-Vercel-black?style=flat-square&logo=vercel"/>
  <img src="https://img.shields.io/badge/Contributors-4-green?style=flat-square"/>
</p>

---

## 📖 About

**Chain Reaction** is a classic two-player strategy game brought to life on the web. Players compete on a grid by placing colored orbs — but when a cell overloads, it **explodes**, sending orbs flying into adjacent cells and potentially setting off a devastating **chain reaction** that can flip the entire board in a single turn.

What makes this version special is its **five elemental themes** — 🔥 Fire, 💧 Water, 🌍 Earth, 💨 Air, and ✨ Ether — each transforming the game with unique background art, color palettes, and ambient soundscapes. The project also includes a **Diagonal Splitting Mode** for an alternative twist on the classic mechanics.

---

## ✨ Key Features

- 🎮 **Classic Chain Reaction Gameplay** — Turn-based strategy on an m × n grid with critical mass explosion mechanics
- 🌋 **5 Elemental Themes** — Fire 🔥 · Water 💧 · Earth 🌍 · Air 💨 · Ether ✨ — each with distinct visuals & audio
- 🎲 **Diagonal Splitting Mode** — An alternate game variant available for every element
- 🔊 **Immersive Sound Design** — Homepage background music, per-element ambient audio, and orb burst sound effects
- 🎥 **3D Animated Carousel** — Stunning element selection screen with CSS 3D transforms and reflections
- 📖 **Built-in Guide** — In-app "How to Play" modal so new players can jump right in
- ⚙️ **Settings & Feedback** — Audio toggle, emoji-based feedback form, and user sign-up panel

---

## 🎯 How to Play

### 🧩 The Board

The game takes place on an **m × n grid**. Every cell has a **critical mass** — the maximum number of orbs it can hold before it explodes. This value depends on how many orthogonal neighbors the cell has:

| Cell Position | Example | Neighbors | Critical Mass |
|:---:|:---:|:---:|:---:|
| ◰ **Corner** | Top-left, Bottom-right | 2 | **2** |
| ▭ **Edge** | Top row (non-corner), Left column | 3 | **3** |
| ◼ **Interior** | Any cell not on the border | 4 | **4** |

### 🔄 Gameplay

| Step | Action | What Happens |
|:---:|---|---|
| **1** | **Place** 🟢🔴 | Players alternate turns. Place an orb in any **empty cell** or a cell that **already has your color**. Orbs in the same cell stack up. |
| **2** | **Explode** 💥 | When a cell's orb count **equals its critical mass**, it bursts! One orb is sent to each orthogonally adjacent cell, and the original cell loses that many orbs. |
| **3** | **Chain React** ⚡ | The explosion may push a neighboring cell past *its* critical mass — triggering another explosion, then another… creating a **cascading chain reaction**! |
| **4** | **Capture** 🔄 | When your explosion reaches an opponent's cell, their orbs are **converted to your color**. |
| **5** | **Win** 🏆 | The last player with orbs remaining on the board **wins the game**! |

---

## 🏗️ Project Structure

```
project_CS3/
├── index.html / homepage.css        # 🏠 Homepage — guide, settings, feedback, sign-up
├── Midpage.html / Midpage.css       # 🎠 Element selection — 3D rotating carousel
├── [element]_mainpage.html / .css   # 🎮 Game boards — one per element (fire, water, earth, air, ether)
├── [element]_mainpagediagonal.html  # 🎲 Diagonal mode — variant for each element
├── [element]bg.jpg / [element]1.jpg # 🖼️ Theme backgrounds & card images
├── [element]sound.mp3               # 🔊 Ambient audio per element
├── burstsound.mp3                   # 💥 Orb explosion sound effect
├── homepagemusic.mp3 / bgimg.jpg    # 🎵 Homepage assets
└── package.json                     # 📦 Project metadata (ISC License)
```

---

## 🚀 Getting Started

**Play Online →** [project-cs-3.vercel.app](https://project-cs-3.vercel.app)

**Run Locally:**
```bash
git clone https://github.com/Puravshah321/project_CS3.git
cd project_CS3
# Open index.html in your browser, or use a local server:
npx serve .
```

---

## 👥 Contributors

Built by a team of **4 contributors** — [view all on GitHub](https://github.com/Puravshah321/project_CS3/graphs/contributors)

---

<p align="center">Made with ❤️ for CS3</p>
