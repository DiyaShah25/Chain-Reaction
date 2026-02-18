<h1 align="center">⚡ Chain Reaction ⚡</h1>

<p align="center">
  <i>A multiplayer strategy board game inspired by the five elements — featuring immersive themes, ambient soundscapes & explosive chain reactions.</i>
</p>

<p align="center">
  <a href="https://project-cs-3.vercel.app"><b>🎮 Play Now → project-cs-3.vercel.app</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-85.9%25-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-14.1%25-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Deployed-Vercel-black?style=flat-square&logo=vercel"/>
</p>

---

## 📖 About

**Chain Reaction** is a two-player strategy game where players take turns placing colored orbs on a grid. When a cell overloads beyond its **critical mass**, it explodes — launching orbs into adjacent cells and potentially setting off a devastating **chain reaction** that can flip the entire board in a single move.

The game comes with **five elemental themes** — 🔥 Fire, 💧 Water, 🌍 Earth, 💨 Air, and ✨ Ether — each with its own unique background art, color palette, and ambient soundtrack. Every element also supports a **Diagonal Splitting Mode** for an alternative gameplay twist.

---

## ✨ Key Features

- 🎮 **Classic Chain Reaction Gameplay** — Turn-based strategy on an m × n grid with critical mass mechanics
- 🌋 **5 Elemental Themes** — Fire 🔥 · Water 💧 · Earth 🌍 · Air 💨 · Ether ✨ — distinct visuals & audio for each
- 🎲 **Diagonal Splitting Mode** — Alternate game variant available for every element
- 🔊 **Immersive Sound Design** — Background music, per-element ambient audio, and burst sound effects
- 🎥 **3D Animated Carousel** — Element selection with CSS 3D transforms and glass reflections
- 📖 **Built-in Guide** — In-app "How to Play" modal for new players
- ⚙️ **Settings & Feedback** — Audio toggle, emoji-rated feedback form, and sign-up panel

---

## 🎯 How to Play

### 🧩 The Board

The game is played on an **m × n grid**. Each cell has a **critical mass** — the maximum orbs it can hold before it explodes:

| Cell Position | Adjacent Neighbors | Critical Mass |
|:---:|:---:|:---:|
| ◰ **Corner** | 2 | **2** |
| ▭ **Edge** | 3 | **3** |
| ◼ **Interior** | 4 | **4** |

### 🔄 Gameplay

| Step | Action | What Happens |
|:---:|---|---|
| **1** | **Place** 🟢🔴 | Players alternate turns. Place an orb in any **empty cell** or a cell **already containing your color**. Orbs in the same cell stack up. |
| **2** | **Explode** 💥 | When a cell's orb count **reaches its critical mass**, it bursts — one orb flies to each orthogonally adjacent cell. |
| **3** | **Chain React** ⚡ | Explosions may push neighboring cells past *their* critical mass, triggering a **cascading chain reaction**! |
| **4** | **Capture** 🔄 | Opponent orbs caught in an explosion are **converted to your color**. |
| **5** | **Win** 🏆 | The last player with orbs on the board **wins**! |

---

## 🏗️ Project Structure

```
Chain-Reaction/
├── index.html / homepage.css        # 🏠 Homepage — guide, settings, feedback, sign-up
├── Midpage.html / Midpage.css       # 🎠 Element selection — 3D rotating carousel
├── [element]_mainpage.html / .css   # 🎮 Game boards (fire, water, earth, air, ether)
├── [element]_mainpagediagonal.html  # 🎲 Diagonal mode variant for each element
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
git clone https://github.com/DiyaShah25/Chain-Reaction.git
cd Chain-Reaction
# Open index.html in your browser, or use a local server:
npx serve .
```

---

## 👥 Contributors

Built by a team of **4 contributors** 
- **Diya Shah** 
- **Purav Shah**
- **Nigam Sanghvi** 
- **Heer Shah** 

---

<p align="center">Made with ❤️ </p>
