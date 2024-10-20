
# Flappy Bird Game (Java with libGDX)

A clone of the classic Flappy Bird game developed using Java and the libGDX framework. This project implements core gameplay mechanics such as obstacle generation, scoring, and collision detection, providing a simple and enjoyable experience.

## Features
- **Obstacle Generation**: Randomly generated pipes that the bird must navigate.
- **Scoring System**: Track your score based on successful navigation through obstacles.
- **Collision Detection**: Detects when the bird collides with pipes or the ground, ending the game.
- **Smooth Graphics and Sound**: Uses libGDX to provide seamless graphics and sound effects for an enhanced user experience.

## How It Works
1. **Bird Movement**: The bird continuously falls due to gravity, with upward movement controlled by user input (spacebar or mouse click).
2. **Obstacles**: Pipes are randomly generated at set intervals and move from right to left across the screen.
3. **Collision Handling**: The game ends when the bird collides with a pipe or the ground.
4. **Scoring**: Points are awarded for each successful navigation through a set of pipes.

## Project Structure
- `src/`: Contains the Java source files, including the game logic, input handling, and rendering.
- `assets/`: Stores all game assets such as images, sounds, and fonts used in the game.
- `README.md`: Detailed description of the project.
- `build.gradle`: Build configuration for the libGDX project.

## Setup and Usage

### Prerequisites
- Java Development Kit (JDK)
- libGDX framework

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Flappy-Bird-Game.git
   cd Flappy-Bird-Game
   ```

2. Build the project:
   ```bash
   ./gradlew desktop:run
   ```

3. Play the game by using the spacebar or mouse click to control the bird.

## Screenshots
(Add screenshots of your game here)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
