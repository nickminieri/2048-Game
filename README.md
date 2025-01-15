# 2048 Game in C

## Overview
This program is a command-line implementation of the classic **2048** game. Players slide tiles on a 4x4 grid using arrow keys to combine numbers and aim to reach the 2048 tile. The game includes win and game-over detection, as well as the ability to track and display the current and highest scores.

## Features
- **Core Gameplay:**
  - Slide tiles using arrow keys (`↑`, `↓`, `←`, `→`).
  - Combine tiles with the same value to create larger numbers.
  - Automatically generate new tiles (2 or 4) after every move.

- **Win/Loss Conditions:**
  - Win by forming a tile with the value `2048`.
  - Lose when no valid moves remain on the board.

- **Scores:**
  - Displays the current score and the highest score.

- **Replay and Exit Options:**
  - Replay after the game ends.
  - Exit anytime by pressing `q` or `Q`.

## How to Use
### Compilation
1. Ensure you have a C compiler (e.g., GCC) installed.
2. Compile the program using the following command:
   ```bash
   gcc -o 2048_game 2048_game.c -Wall -g -lm
   ```

### Running the Game
1. Run the compiled program:
   ```bash
   ./2048_game
   ```
2. Use the arrow keys to slide the tiles:
   - **`↑`**: Slide tiles upward.
   - **`↓`**: Slide tiles downward.
   - **`←`**: Slide tiles to the left.
   - **`→`**: Slide tiles to the right.
3. To quit the game at any time, press `q` or `Q`.
4. After the game ends, choose whether to replay or exit.

### Example Gameplay
#### Initial Board:
```
*** Score = 0, High Score = 0 ***
-------------------------
|     |     |     |     |
-------------------------
|     |     |     |     |
-------------------------
|     |     |     |     |
-------------------------
|     |     |  2  |  2  |
-------------------------
```

#### After Sliding Right:
```
*** Score = 4, High Score = 4 ***
-------------------------
|     |     |     |     |
-------------------------
|     |     |     |     |
-------------------------
|     |     |     |     |
-------------------------
|     |     |     |  4  |
-------------------------
```

## Development Notes
- **Programming Concepts:**
  - Arrays and Matrices
  - Keyboard Input Handling
  - Game Logic and Systematic Sequential Logic

- **Testing:**
  - Written and tested in Visual Studio Code.
  - Verified with `gcc` on CES Ubuntu for error-free compilation.

## Improvements
Future enhancements could include:
- Adding more polished UI or colors for better gameplay experience.
- Implementing a smarter random tile placement algorithm.
- Adding undo functionality.

## Author
Nicholas Minieri
