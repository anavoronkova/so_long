# So Long

## And Thanks for All the Fish!

## Summary
**So Long** is a small 2D game developed in C using the MiniLibX library. The player collects items and escapes through a designated exit, enhancing skills in graphics, textures, and basic gameplay.

## Introduction
**So Long** is a 2D game created to learn window management, event handling, textures, and C programming. The player must collect all items and find the exit on a 2D map.

## Installation
1. Clone the repository:
   ```
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```
   cd so_long
   ```
3. Compile the project:
   ```
   make
   ```

## Usage
Run the game with:
```
./so_long <map_file.ber>
```
Replace `<map_file.ber>` with the map file path.

## Features
- **Collect all collectibles and find the exit**.
- **Movement**: Use `W`, `A`, `S`, `D` or arrow keys to move.
- **Move Count**: Displays the move count in the terminal.
- **2D View**: Top-down or profile view of the game.
- **Exit Options**: Press `ESC` or click the window cross to exit the game.
- **Map Elements**:
  - `0`: Empty space
  - `1`: Walls
  - `C`: Collectibles
  - `E`: Exit
  - `P`: Start position

