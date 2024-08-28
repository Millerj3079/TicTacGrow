# Tic Tac Grow

Tic Tac Grow is an expanded version of the classic Tic Tac Toe game, now supporting up to 9 players. The game starts with a 3x3 grid, and whenever a player achieves 3 in a row, the board expands outward by one square. Players earn points by achieving streaks (3 in a row, 5 in a row, etc.), and the first player to reach 5 points wins.

## Gameplay

1. **Starting the Game**:
    - The game begins on a 3x3 grid.
    - Players are identified by numbers (1-9), with each player assigned a unique color.
    - Upon load or reset, the game prompts for the number of players.

2. **Scoring**:
    - Players earn 1 point for completing a streak (3 in a row, 5 in a row, etc.).
    - After achieving a streak, the player continues to build upon their success, with the next goal increasing to the next odd number (e.g., from 3 to 5).

3. **Continuing Play**:
    - Players take turns placing their marks on the board.
    - When a player completes a streak, the board expands outward, and the streak's cells are marked with the player’s color.
    - Players can continue to build on prior successes, using previously successful streaks in subsequent turns.

4. **Winning**:
    - The first player to reach 5 points wins the game.

## How to Play

- **Step 1**: Start the game by entering the number of players (1-9) when prompted.
- **Step 2**: Players take turns placing their marks on the board by clicking an empty cell.
- **Step 3**: After achieving a streak (e.g., 3 in a row), the player earns a point, and the board expands.
- **Step 4**: The game continues with the next streak target (e.g., 5 in a row) until one player reaches 5 points.

## Visual Aids

- **Player Colors**: Each player is assigned a unique color, which is used to mark cells involved in completed streaks.
- **Board Expansion**: After each successful streak, the board expands outward to accommodate the growing challenge.
- **Streak Tracking**: The current streak target and points for each player are displayed, helping players keep track of their progress.

## Demo

Play the game [here](https://yourusername.github.io/tic-tac-grow).

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/tic-tac-grow.git
    ```
2. **Navigate to the Project Folder**:
    ```bash
    cd tic-tac-grow
    ```
3. **Open `index.html` in a Web Browser** to play locally.

## Technologies Used

- **HTML**: For the structure of the game.
- **CSS**: For styling the game interface.
- **JavaScript**: For game logic and dynamic interaction.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

## Contributing

If you'd like to contribute to Tic Tac Grow, please fork the repository, create a new branch for your feature or bugfix, and submit a pull request. Contributions are welcome!