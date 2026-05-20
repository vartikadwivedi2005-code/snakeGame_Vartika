# 🐍 HTML5 Canvas Snake Game 🎮

Welcome to this sleek, lightweight **Snake Game** built completely from scratch using **HTML5 Canvas** and modern, vanilla **JavaScript**! Guide your hungry snake, gobble up the food, rack up points, and avoid smashing into the walls. 

---

## ✨ Features

*   **🎨 Canvas Rendering:** Smooth, responsive 2D graphics powered by the HTML5 Canvas API.
*   **🍉 Smart Food Spawning:** Food pops up randomly across the arena, perfectly aligned to our $50\text{px}$ grid block system.
*   **💯 Real-time Scoreboard:** An on-screen score overlay that updates instantly when you eat.
*   **🚫 Collision Guard:** Instant wall-collision detection that automatically brings up a neat **Game Over** screen.

---

## 🕹️ How to Play

1.  **⌨️ Controls:** Navigating your snake is easy! Just use your keyboard's **Arrow Keys**:
    *   `ArrowUp` 🔼 — Move Up
    *   `ArrowDown` 🔽 — Move Down
    *   `ArrowLeft` ◀️ — Move Left
    *   `ArrowRight` ▶️ — Move Right *(Note: Any unassigned key will default your direction to the right!)*
2.  **🎯 Goal:** Direct your bright neon-blue snake to swallow the neon-pink food blocks.
3.  **📈 Grow:** Every piece of food eaten extends the snake's body and builds up your score.
4.  **💀 Game Over:** Stepping out of bounds ($1000\text{px}$ wide by $600\text{px}$ high) will instantly end your run.

---

## 📁 Project Structure

```text
📂 snake-game
├── 📄 index.html   # 🏗️ Setup, layout, and arena styling
└── 📄 index.js     # 🧠 Core game loop, controls, and logic
