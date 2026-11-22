# 🐍 Snake Game

A classic desktop Snake Game built with **Java** and **Java Swing**. This application allows players to control a snake, collect apples, increase their score, and avoid collisions in a simple interactive gaming environment.

## ✨ Features

- **🎮 Snake Movement**:
  - Control the snake using the arrow keys.
  - Smooth movement with automatic game updates.
- **🍎 Apple Collection**:
  - Apples appear at random positions on the game screen.
  - Each apple collected increases the score and the snake's length.
- **💥 Collision Detection**:
  - Detects collisions with the game boundaries.
  - Detects collisions between the snake's head and its body.
  - Ends the game when a collision occurs.
- **🔄 Restart Game**:
  - Restart the game by pressing the `R` key after Game Over.
- **📊 Score Tracking**:
  - Keeps track of the number of apples collected.

## 🛠️ Technical Architecture

This project follows the **Object-Oriented Programming (OOP)** paradigm and uses Java Swing to create the graphical interface.

- **Game Window**: Uses `JFrame` to create the main application window.
- **Game Panel**: Uses `JPanel` and `Graphics` to draw the snake, apples, and game elements.
- **Event Handling**: Uses `KeyAdapter` to handle keyboard input.
- **Game Loop**: Uses `javax.swing.Timer` to control movement and refresh the game.
- **Random Generation**: Uses Java's `Random` class to generate apple positions.

## 🚀 How to Run

1. **Prerequisites**: Ensure you have Java JDK installed.
2. **Clone the Repository**:

   ```bash
   git clone https://github.com/nananoui/Snake-Game.git
   ```
3. **Open the Project**: Open the project folder in your preferred Java IDE, such as VS Code.
4. **Run the Application**: Run the `Snakegame.java` file.

## 🎨 Game Design

The game features a simple graphical interface with a black background, a green snake, and red apples.

---

