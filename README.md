# Super Mario Clone

A polished 2D side-scrolling platformer built with HTML5 Canvas and React. This project demonstrates physics-based movement, enemy AI, a dynamic camera system, and interactive collectables.

## 🚀 Live Demo
- **Shared App:** [View Live App](https://ais-pre-upriddd4ap5k6izerkf5ge-250246974472.europe-west1.run.app)

## 🎮 Gameplay Features
- **Smooth Physics:** Implement jump mechanics, gravity, and precise collision detection.
- **Dynamic Camera:** A side-scrolling camera that follows the player smoothly.
- **Variety of Enemies:**
  - **Walkers:** Classic ground-based enemies that patrol platforms.
  - **Flyers:** Floating enemies that move in a sine-wave pattern.
  - **Shooters:** Stationary units that fire projectiles directly at the player.
- **Collectables:** Gold coins scattered throughout the level that increase your score and play a chime.
- **Objective:** Navigate the terrain, defeat or dodge enemies, and reach the red flagpole to clear the course.

## ⌨️ Controls
| Action | Key(s) |
| :--- | :--- |
| **Move Left** | `ArrowLeft` or `A` |
| **Move Right** | `ArrowRight` or `D` |
| **Jump** | `ArrowUp`, `W`, or `Space` |
| **Restart Game** | Click 'Play Again' button after Game Over |

## 🛠️ Technical Stack
- **Frontend Framework:** [React 19](https://react.dev/)
- **Rendering:** HTML5 Canvas API
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animation:** `requestAnimationFrame` for a smooth 60FPS game loop.
- **Audio:** Web Audio API (Synthesized sound effects)
- **Icons:** [Lucide React](https://lucide.dev/)

## 🏗️ Development Setup

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Run Development Server:**
   ```bash
   npm run dev
   ```

3. **Build for Production:**
   ```bash
   npm run build
   ```

## 📜 License
This project is licensed under the Apache-2.0 License.
