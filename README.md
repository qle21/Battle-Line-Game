# Battleship Game in Java

## Overview
This is a simple console-based Battleship game implemented in Java. The game allows two players to take turns to guess the locations of each other's ships on a grid. The player who sinks all the opponent's ships first wins the game.

## Features
- Grid-based gameplay.
- Two-player mode.
- Ships of different sizes.
- Display of hits and misses.
- Game status updates.

## How to Play
1. **Compile and Run:**
    - Compile the Java files: `javac Main.java`
    - Run the game: `java Main`

2. **Setup:**
    - Each player places their ships on the grid.
    - Players take turns to guess coordinates to attack.

3. **Gameplay:**
    - Enter coordinates (e.g., "A3") to attack.
    - The console will display if it's a hit or miss.
    - Keep attacking until all ships are sunk.
![Uploading 2024-01-13 16.36.29.png…]()


4. **Winning:**
    - The first player to sink all opponent's ships wins.
    - The game ends, and the winner is announced.

## Game Components
- **Main.java:** Contains the main method to start the game.
- **Board.java:** Manages the game board, grid, ships, and attacks.
- **Ship.java:** Defines the Ship class with methods for placing and checking hits.
- **Player.java:** Manages player-specific actions and information.

## Customization
- Adjust the grid size, ship types, or any game rules in the code.
- Customize the display messages or add more features as needed.

## Example Code
```java
// Example code to create a game instance
public class Main {
    public static void main(String[] args) {
        BattleshipGame game = new BattleshipGame();
        game.start();
    }
}


