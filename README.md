# Tetromino Game
## Overview
This project is a Tetris-like game implemented in Go. The goal of the game is to place Tetromino pieces on a 10x10 grid. When a full row (horizontal or vertical) is formed, the row is cleared, and points are awarded. The more rows cleared with a single move, the more points are awarded. The game will also include features like a start screen, game-over screen, and support for textured blocks and other UI improvements such as animations.

## Project Status
Currently, this project is in its early development phase. No functionality has been implemented yet, but the window setup and game loop structure are being established using the go-sdl2 library.

## Technology Stack
- **Programming Language**: Go
- **Graphics and Window Management**: SDL via go-sdl2
- **Project Structure**: Modular with feature-based branching

## How to Get Started
To set up the project and run the initial window setup (once it's implemented), follow the steps below:

### 1. Clone the Repository
```bash
git clone https://github.com/username/go-tetromino-game.git
cd go-tetromino-game
```
### 2. Install Go-SDL2
Make sure you have Go installed on your system. Install the SDL2 dependencies for your platform:

**On macOS (with Homebrew):**
```bash
brew install sdl2 sdl2_image sdl2_mixer sdl2_ttf
```

**On Linux (Ubuntu):**
```bash
sudo apt-get install libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev
```

**On Windows:**
- You will need to download and set up the SDL2 development libraries manually. Instructions are available on the SDL2 website.


Then install the go-sdl2 package:

```bash
go get -v github.com/veandco/go-sdl2/sdl
```
### 3. Run the Project (Once Implemented)
Once the window and game loop are implemented, you'll be able to run the game with the following command:
```bash
go run main.go
```

## Development
Development will follow a feature-based approach, with each major functionality developed in separate branches before being merged into the main branch.

### Upcoming Features:
- [ ] Window creation and game loop
- [ ] Basic game grid and rendering
- [ ] Tetromino placement and logic
- [ ] Row detection, scoring system and other related logic
- [ ] Start screen and game over screen
- [ ] Textured tetrominos and other UI improvements
