# 2048 Game

A responsive web version of the classic 2048 puzzle game built with React and TypeScript. Slide tiles on a 4×4 grid, merge matching numbers and try to reach the 2048 tile.

## Live Preview

[![Live Demo](https://img.shields.io/badge/🎮_Play_Now-Open_Game-edc22e?style=for-the-badge)](https://droopy-bit.github.io/2048game/)

Deployed on GitHub Pages: [https://droopy-bit.github.io/2048game/](https://droopy-bit.github.io/2048game/)

## Technologies Used

**Core**
- HTML5
- SCSS / CSS
- JavaScript (ES6+, ES modules)

**Deployment**
- GitHub Pages
## Getting Started

Follow these steps to set up the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/droopy-bit/2048game.git
cd 2048game
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the project locally

```bash
npm start
```

The game will be available at the address shown in your terminal.

## How to Play

- Use the **arrow keys** or **WASD** to slide all tiles in one direction
- On mobile, **swipe** in the direction you want to move
- When two tiles with the same number touch, they **merge** into one
- Reach the **2048** tile to win
- The game ends when no moves are left

## Features

- **Classic gameplay** — 4×4 grid with tile sliding and merging
- **Score tracking** — the score grows with every merge
- **Best score** — saved in `localStorage`, so it survives page reloads
- **Smooth animations** — sliding, spawning and merging of tiles
- **Keyboard and touch controls** — arrow keys, WASD and swipe gestures
- **Responsive design** — works on any screen size
