# Mario Bros. Clone (C Project)

## Overview
This project is a 2D side-scrolling platformer game implemented in C, inspired by classic games like Super Mario Bros. The game features basic gameplay mechanics, such as moving left and right, jumping, collecting items, and avoiding obstacles.

## Features
- Basic movement controls (left/right, jump)
- Collectible items (coin)
- Obstacles (bricks, pitfalls)
- Simple level design

## Project Structure
```
mario_bros_clone/
├── Makefile
├── include/
│   ├── sprite.h
│   ├── rect.h
│   ├── figure.h
│   ├── world.h
│   └── ...
├── src/
│   ├── main.c
│   ├── sprite.c
│   ├── rect.c
│   ├── figure.c
│   ├── world.c
│   └── ...
└── assets/
    ├── images/
    │   ├── player.png
    │   ├── ground.png
    │   ├── brick.png
    │   ├── coin.png
    │   └── ...
    └── sounds/
        ├── jump.wav
        ├── collect_coin.wav
        └── ...
```

## Build & Run

### Prerequisites
- C/C++ Compiler (GCC, Clang, or MSVC)
- Make utility
- Standard development tools
- SDL2 library for rendering and input handling (optional)

### Build Steps

```bash
cd mario_bros_clone
make clean  # Optional, if you want to remove previous build files
make all    # Compile the project

If SDL2 is used:

make lib    # Compile the library
./build/Main  # Run the game

or

make exe   # Directly compile and run the executable
```

This Makefile should be adjusted based on your development environment and available libraries. If SDL2 is not used, some parts of the code related to rendering might need adjustments or removals.