# 🕹️ HTML Neon Games Collection

Welcome to the **HTML Neon Games Collection**! This repository hosts a couple of impressive, retro-inspired, hyper-neon aesthetic web games. Built entirely from scratch using **Vanilla JavaScript** and **HTML5 Canvas**, this project requires absolutely no external dependencies or WebGL libraries.

Dive into a world of glowing grids, 80s arcade vibes, and raw JavaScript power.

---

## 🎮 Games Included

### 1. Neon Assault: 2.5D FPS Raycaster
**File:** `Shooter.html`

A high-fidelity, fully functional 2.5D First-Person Shooter engine. Inspired by classics like *Wolfenstein 3D* and *Doom*, this engine mathematically projects a 2D map array into an immersive 3D space.

**Key Features:**
* **Raycasting Engine:** Built purely with JS logic, executing the Digital Differential Analyzer (DDA) algorithm for wall projection.
* **Retro Aesthetics:** Fixed pseudo-resolution dynamically upscaled for that crunchy, pixelated hit of nostalgia.
* **Hitscan Combat:** Accurately calculates line-of-sight and depth buffer to verify your shots using the mouse crosshair.
* **Native Controls:** Seamless WASD movement paired with native browser **Pointer Lock** for realistic Mouse Look.
* **Tactical Minimap:** An overlaid, real-time minimap showcasing your position, FOV directional cone, and active targets in the maze.

### 2. Neon Snake Game
**File:** `index.html`

A blazing-fast, glow-in-the-dark adaptation of the classic Snake formula, pushing modern `<canvas>` shadows to its limits.

**Key Features:**
* **Grid Wrapping:** Drive off one edge of the screen and warp safely to the other side to keep your combo alive.
* **Progressive Difficulty:** Speed intensifies dynamically with every 50 points accumulated.
* **Persistence:** Leverages `localStorage` to save your highest scores across sessions.
* **Vibrant Visuals:** Intense neon colors dropping heavy shadows and bloom effects across a moody grid.

---

## 🚀 How to Play

No build processes, no npm installs, no bundlers. Pure vanilla web development.

1. Clone the repository to your local machine (adjust the URL if you fork it):
   ```bash
   git clone https://github.com/your-username/HTML-Games.git
   ```
2. Navigate into the directory and open either `index.html` (Snake) or `Shooter.html` (FPS) directly in your favorite modern web browser.
3. Enjoy!

*(Note: The Pointer Lock API used in Neon Assault works best when the file is run through a local server like VS Code's "Live Server" extension, but it is generally playable directly from the file system).*

---

## 🛠️ Technology Stack
- **HTML5 Canvas:** Rendering API for drawing 2D paths, geometric sprites, and rays.
- **Vanilla JavaScript:** All game logic, raycasting math, inverse matrix calculations, and state management.
- **CSS3:** For deep drop-shadows, UI overlays, and retro pixelated rendering.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! 
Feel free to start extending the Raycaster engine, refine the graphics, or propose a brand new glowing mini-game for the collection.
