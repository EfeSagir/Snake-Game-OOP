Snake Game (OOP) 🐍

A clean, modular implementation of the classic Snake game logic developed in Python using the Turtle library. This project demonstrates the application of Object-Oriented Programming (OOP) to manage game states and entity behaviors.

🛠️ Technical Overview

Modular Design: The project is organized into distinct classes for the snake, food, and scoreboard to ensure separation of concerns.

Event Handling: Utilizes the screen.onkey method to capture real-time keyboard inputs for directional control.

Boundary Logic: Includes collision detection that monitors coordinates to trigger a game-over sequence if the snake leaves the playable area.

Score Management: Features a dedicated Scoreboard class that handles UI updates and score increments whenever food is consumed.

📂 File Structure

main.py: Orchestrates the game loop, screen updates, and collision logic.

snake.py: Defines the snake's initial structure, movement patterns, and directional constraints.

food.py: Handles the randomized positioning and appearance of the target food.

scoreboard.py: Manages the visual display of the score and the game-over message.
