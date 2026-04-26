# Project README

## Overview
This project is a simple 2D platformer game written in C. The player can move left and right, jump, and collide with various blocks in the environment.

## Features
- Player movement (left, right)
- Jumping mechanics
- Collision detection with solid blocks
- Basic rendering of player sprite

## Project Structure
```
<Project>/
├── assets/             # Contains images and sound files
│   ├── player.png      # Player sprite image
│   └── background.png  # Background image
├── src/                # Source code
│   ├── Main.c          # Entry point of the program
│   ├── Figure.h        # Header file for player functionality
│   ├── Figure.c        # Implementation of player functionality
│   └── World.h         # Placeholder header file for world map handling (not implemented)
├── README.md           # This file
└── Makefile.linux      # Linux Build configuration
```

### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
To build the project on Linux, follow these steps:
1. Navigate to the project directory.
2. Run `make -f Makefile.linux all` to build the project.

To run the compiled executable:
1. Run `make -f Makefile.linux exe`.

This will produce an executable file named `./build/Main(.exe)` in the root directory of the project, which can be run directly.