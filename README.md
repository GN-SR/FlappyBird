# Flappy Bird Game

A simple implementation of the classic Flappy Bird game using Java. This project is designed for learning purposes and showcases basic game development principles such as graphics rendering, event handling, and collision detection in Java.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)


---

## Features
- **Pixel-perfect Gameplay**: Fly the bird through pipes while avoiding collisions.
- **Scoring System**: Tracks and displays your current score.
- **Lightweight**: No external libraries required—just plain Java.

---

## Prerequisites
To run this project, ensure you have the following installed:
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) (version 8 or higher)
- An IDE or text editor for Java (e.g., [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Eclipse](https://www.eclipse.org/), or [VS Code](https://code.visualstudio.com/))

---

## Installation
1. **Clone the Repository**  
   Clone this repository to your local machine:
   
   ```bash
   git clone https://github.com/GN-SR/FlappyBird
   cd FlappyBird
   ```

2. **Compile the Code**
   Navigate to the project directory and compile the Java files:

   ```bash
   javac src/*.java
   ```

3. **Run the Game**
   Execute the compiled files to start the game:
   ```bash
   java src.App
   ```
---

## Usage
1. **Start the Game**
2. 
    Run the game using the instructions above. A new window will open showing the game screen.

3. **Controls**

    -Press the Spacebar to make the bird jump.
    -Avoid the pipes and try to achieve the highest score possible.
   
3. **Restart**
    If you collide with a pipe or fall of the ground, the game ends. You can restart by pressing SpaceBar or closing and reopening the game.

---

## How It Works

   The game is built using basic Java features:

   -Graphics Rendering: Utilizes javax.swing and java.awt for rendering the game window, bird, and pipes.
   -Game Loop: A simple loop to update the game's state and redraw the screen at a consistent frame rate.
   -Collision Detection: Checks if the bird intersects with any pipes or the ground.
   -Scoring: Increments the score each time the bird successfully passes between a pair of pipes.

---
