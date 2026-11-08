2048 Game — Modern Web Implementation
A sleek, responsive, and fully functional implementation of the classic 2048 puzzle game built using modern web technologies. Players merge tiles with matching numbers by sliding them in four directions to achieve the target score of 2048 and beyond.

Live Preview
- Live Demo (https://droopy-bit.github.io/2048game/)

Note: Make sure to test the link in Incognito Mode to verify functionality without browser caching issues.

Design Reference
Original Game Concept: 2048 by Gabriele Cirulli

Technologies Used
Core
React (v18.x) — UI Component Library

TypeScript (v5.x) — Type Safety and Static Analysis

SCSS / CSS Modules — Modular and Maintainable Styling

Development & Deployment
Vite (v5.x) — Lightning-fast Build Tool & Dev Server

ESLint / Prettier — Code Quality and Formatting

GitHub Pages — Hosting and Automated Deployment (gh-pages)

Getting Started
Follow these instructions to set up and run the project locally on your machine.

1. Clone the repository:
Bash
git clone https://github.com/droopy-bit/2048-game.git
cd 2048-game
2. Install dependencies:
Bash
npm install
3. Run the project locally:
Bash
npm run dev
Open http://localhost:5173 in your browser to view the app.

Features
Smooth Tile Animations: Fluid sliding, spawning, and merging transitions.

Touch & Keyboard Controls: Full support for arrow keys (and WASD) on desktop, as well as swipe gestures on mobile devices.

Score & Best Score Tracking: Real-time current score calculation with persistent high score saved via localStorage.

Game Over & Victory States: Clear notifications when no valid moves remain or when the 2048 tile is achieved, with an option to continue playing.

Restart / Reset Button: Instantly start a new game at any time.

Fully Responsive Design: Optimized layout for smartphones, tablets, and desktop displays.
