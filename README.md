# SUSU-IN-THE-MAZE
# Top-Down Adventure Game

This is a **top-down adventure game** built using the [LÖVE 2D framework](https://love2d.org/). The game features a dynamic player-controlled character navigating a map, interacting with objects, and switching between various game states, such as menu, play, pause, and options.

## Features

- **Dynamic Game States**: Includes `menu`, `play`, `pause`, `options`, and `end` states for seamless gameplay.
- **Interactive Menus**: Navigate through options like starting the game, toggling sound, and exiting.
- **Player Mechanics**:
  - Four-directional movement with animations.
  - Collision detection with walls and map boundaries.
- **Game Map**:
  - A dynamic map loaded via `Tiled` (using the `STI` library).
  - Includes static and interactive elements like doors and walls.
- **Sound Effects and Music**: Background music and button interaction sounds.
- **Camera**: Smooth camera movement that follows the player across the map.

## Setup and Installation

### Prerequisites

- Install the [LÖVE 2D framework](https://love2d.org/) (version 11.x or later).

### Game Files

Ensure the following folder structure is present in the project directory:

```
/project-root
│
├── libraries/
│   ├── windfield.lua       # Physics engine library
│   ├── camera.lua          # Camera functionality
│   ├── anim8.lua           # Animation library
│   ├── sti.lua             # Tiled map loader
│
├── maps/
│   └── map.lua             # Tiled map file
│
├── sprites/
│   ├── player-sheet.png    # Sprite sheet for player animations
│   ├── door.png            # Door sprite
│
├── backgrounds/
│   └── startScreen.png     # Background image for the start menu
│
├── sounds/
│   ├── blip.wav            # Button interaction sound
│   ├── music.mp3           # Background music
│
└── main.lua                # Main game code
```

### How to Run

1. Clone the repository or download the project as a ZIP file.
2. Open the project directory in your terminal.
3. Run the game using the LÖVE framework:
   ```bash
   love .
   ```

## Gameplay Instructions

1. **Menu Navigation**:
   - Use the arrow keys (`left`/`right`) to navigate between options.
   - Press `Enter` to select an option.
2. **Game Play**:
   - Control the player with the arrow keys (`up`, `down`, `left`, `right`).
   - Explore the map and avoid obstacles.
3. **Pause Menu**:
   - Press `ESC` during gameplay to pause the game and access additional options.
4. **Options Menu**:
   - Toggle the background music on/off.
   - Return to the main menu.

## Dependencies

The project uses the following libraries:
- [Windfield](https://github.com/adnzzzzZ/windfield): Physics engine for collision detection.
- [Anim8](https://github.com/kikito/anim8): Animation library for sprite sheets.
- [STI](https://github.com/karai17/Simple-Tiled-Implementation): Tiled map loader.
- [Camera](https://github.com/vrld/hump): Camera library for dynamic viewing.

## Future Enhancements

- Add more levels with increasing difficulty.
- Introduce interactive items and power-ups.
- Enhance visual effects and animations.
- Implement a scoring system and leaderboard.

## License

This project is open-source and available under the MIT License. Feel free to contribute or modify the game.

---

Enjoy playing the Top-Down Adventure Game! 🎮
```
