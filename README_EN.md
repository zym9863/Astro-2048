# Astro 2048

A classic 2048 number puzzle game developed with the Astro framework.

[🇨🇳 中文版](README.md)

## 🎮 Game Introduction

2048 is a simple yet challenging number puzzle game. Players slide tiles to merge identical numbers, aiming to reach the number 2048.

### Game Rules
- Use arrow keys (up, down, left, right) to move tiles
- Tiles with the same number merge into a larger number when they collide
- After each move, a new tile (2 or 4) is randomly generated
- The game ends when no more moves are possible
- Reach 2048 to win!

### Game Features
- 🎯 Classic 2048 gameplay
- 🎨 Beautiful interface design
- 📱 Responsive layout for all devices
- ⌨️ Keyboard control (arrow keys)
- 🔄 Restart the game anytime
- 📊 Real-time score display

## 🚀 Project Structure

```text
/
├── public/
│   └── favicon.svg          # Website icon
├── src/
│   ├── assets/
│   │   ├── astro.svg        # Astro logo
│   │   └── background.svg   # Background pattern
│   ├── components/
│   │   ├── Game.astro       # Main 2048 game component
│   │   └── Welcome.astro    # Welcome component
│   ├── layouts/
│   │   └── Layout.astro     # Page layout component
│   └── pages/
│       └── index.astro      # Homepage
├── astro.config.mjs         # Astro config file
├── package.json             # Project dependencies and scripts
└── tsconfig.json            # TypeScript config
```

### Core File Descriptions
- `src/components/Game.astro`: Contains the complete 2048 game logic, including:
  - Game state management
  - Tile movement and merging logic
  - Keyboard event handling
  - Game UI rendering
  - Score calculation and display
- `src/pages/index.astro`: Game homepage, imports and displays the game component
- `src/layouts/Layout.astro`: Basic page layout, sets up HTML structure and base styles

## 🕹️ How to Play

1. **Start the Game**: The game initializes automatically and displays two starting tiles
2. **Move Tiles**: Use arrow keys to control tile movement
   - ↑ Up
   - ↓ Down
   - ← Left
   - → Right
3. **Merge Tiles**: Tiles with the same number merge and double their value
4. **Score Points**: Each merge increases your score
5. **Win Condition**: Create a 2048 tile
6. **Lose Condition**: The board is full and no moves are possible

## 🛠️ Technical Implementation

### Core Tech Stack
- **Astro**: Modern frontend framework for fast websites
- **TypeScript**: Type-safe JavaScript development
- **CSS3**: Pure CSS for game UI and animations

### Game Logic Implementation
- **State Management**: Uses a 4x4 2D array to manage the game board state
- **Movement Algorithm**: Implements movement and merging logic for all four directions
- **Random Generation**: Generates new tiles in empty spaces after each move
- **Win/Lose Detection**: Checks for victory and game over conditions
- **Event Handling**: Listens for keyboard events to control the game

## 🧞 Development Commands

All commands should be run in the project root directory terminal:

| Command                  | Description                              |
| :----------------------- | :--------------------------------------- |
| `pnpm install`           | Install dependencies                     |
| `pnpm dev`               | Start local dev server `localhost:4321`  |
| `pnpm build`             | Build production code to `./dist/`       |
| `pnpm preview`           | Preview build locally                    |
| `pnpm astro ...`         | Run Astro CLI commands, e.g. `astro add` |
| `pnpm astro -- --help`   | Get Astro CLI help                       |

## 🚀 Quick Start

1. **Clone the project**
   ```bash
   git clone https://github.com/zym9863/Astro-2048.git
   cd Astro-2048
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start the dev server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**
   Visit `http://localhost:4321` to start playing!

## 🎯 Game Highlights

### Beautiful Interface
- Classic 2048 color scheme
- Smooth number transition animations
- Clear game state feedback
- Responsive design for all screens

### Full Features
- ✅ Complete game logic
- ✅ Real-time score tracking
- ✅ Win detection
- ✅ Game over detection
- ✅ One-click restart
- ✅ Keyboard control support

### Technical Highlights
- ⚡ Astro static site generation for fast loading
- 🔒 TypeScript type safety
- 🎨 Pure CSS animations for great performance
- 📦 Zero external dependencies
- 🔧 Easy to extend and customize

## 📝 License

This project is open-sourced under the MIT License. See the LICENSE file for details.

## 🤝 Contributing

Feel free to submit Issues and Pull Requests to improve this project!

---

**Enjoy the fun of 2048!** 🎮✨
