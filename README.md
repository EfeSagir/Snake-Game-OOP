# Snake Game Engine (OOP) 🐍

A modular 2D game engine developed in Python using the **Turtle** graphics library. This project implements an object-oriented architecture to handle real-time coordinate tracking, entity growth, and collision physics.

## 🚀 Engine Features

- **Dynamic Movement Engine**: Utilizes a segment-following algorithm where each part of the snake inherits the position of the previous segment.
- **Collision Detection Logic**: Real-time monitoring of coordinates to detect boundaries and interactions with food objects.
- **Automated State Management**: Centralized control for game-over sequences and scoreboard refreshes.
- **Recursive Entity Generation**: A food system that respawns at randomized coordinates upon collision.

## 🛠️ Project Structure

- `main.py`: The core game loop that orchestrates screen updates and collision checks.
- `snake.py`: Manages the creation, movement, and directional constraints of the snake entity.
- `food.py`: Handles the randomized appearance and positioning of target objects.
- `scoreboard.py`: A dedicated UI module for real-time score tracking and endgame messaging.

## 🎮 How to Run

1.  Ensure Python is installed.
2.  Run the engine:
    ```bash
    python main.py
    ```
3.  Use **Arrow Keys** to control the snake.
