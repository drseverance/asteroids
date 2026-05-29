# Asteroids

A simple 2D Asteroids-style game built with Python and Pygame.

## Features

* Player movement with rotation
* Delta-time based movement
* 60 FPS game loop
* Object management using Pygame sprite groups
* Game state logging

## Controls

| Key | Action        |
| --- | ------------- |
| W   | Move forward  |
| S   | Move backward |
| A   | Rotate left   |
| D   | Rotate right  |

## Requirements

* Python 3.13+
* Pygame
* uv package manager

## Installation

Clone the repository:

```bash
git clone https://github.com/drseverance/asteroids.git
cd asteroids
```

Install dependencies:

```bash
uv sync
```

## Running the Game

Start the game with:

```bash
uv run main.py
```

## Project Structure

```text
asteroids/
├── main.py
├── player.py
├── circleshape.py
├── constants.py
├── logger.py
├── game_state.jsonl
├── .gitignore
└── README.md
```

## Current Progress

The project currently includes:

* Pygame window and render loop
* Player rendering
* Rotation and movement
* FPS limiting using delta time
* Sprite groups for updating and drawing

## Future Plans

* Asteroids
* Collision detection
* Shooting mechanics
* Score system
* Sound effects
* Game over screen

## License

This project is for educational purposes.
