# 🎮 Dream Blast

**Dream Blast** is a top-down 2D puzzle-action game built in **GDevelop** for my CMPM 80K final project.  
The player takes the role of a superhero navigating through a child’s nightmare, defeating enemies and solving environmental puzzles to escape each level.

---

## ✨ Features

- **Core Mechanics**
  - Continuous top-down movement with enemy patrol AI
  - Superpower ability to spawn **clones** that can distract enemies or stand on pressure plates
  - Puzzle interactions such as doors that unlock only when clones hold switches
  - Combat: defeat nightmare monsters while conserving limited clone resources

- **Technical Highlights**
  - Built with **GDevelop 5** using event sheets (no raw engine code required)
  - Organized reusable events for **AI behavior, collision handling, and power mechanics**
  - Custom **state-based enemy AI**: idle → chase → attack
  - Original art assets contributed by the team (pixel-style characters, UI, and level tilesets)
  - Integrated **sound design and background music** for immersive atmosphere
  - Demonstrates **game architecture principles** transferable to larger game engines (Unity, Godot)

## 🛠️ Tech Stack

- **Engine:** GDevelop 5 (extended with **custom JavaScript**)  
- **Codebase:** 1,000+ lines of JavaScript powering complex mechanics (e.g., timeline system, enemy AI, clone spawning)  
- **Key Technical Features:**
  - Timeline mechanic for recording and replaying player actions
  - JSON-based parsing of action data for MOVE and BOMB events
  - Dynamic instantiation of timeline objects bound to player IDs
  - Modular JavaScript functions integrated with GDevelop’s event system

---

## 🚀 How to Run

### Option 1: Play the Exported Build
If we’ve uploaded an HTML5 export:
1. Clone or download this repo.
2. Open the `dist/` or `export/` folder in your browser (`index.html`).
3. Play instantly, no install required.

### Option 2: Open in GDevelop (Recommended for Contributors)
1. [Download GDevelop 5](https://gdevelop.io/download).
2. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/dream-blast.git
   cd dream-blast
