# Snake and Ladder

This is a Python implementation of the classic Snake and Ladder board game using the Tkinter library for the graphical user interface (GUI). The game allows two players to compete, with the goal of reaching the 100th square on the board. The game features ladders that boost the player's position and snakes that bring them back down.

## Features

- **Two-Player Mode**: Supports two players, each represented by a different color on the board.
- **Interactive Dice**: Players click a button to roll the dice, and their piece moves according to the number rolled.
- **Snakes and Ladders**: Includes classic game mechanics where landing on a ladder moves the player up, and landing on a snake moves them down.
- **Graphical Interface**: Built using Tkinter, providing an easy-to-use interface with a graphical representation of the game board.
- **Victory Detection**: The game automatically detects when a player reaches the 100th square and declares them the winner.

## How It Works

1. **Game Setup**: The board is initialized with two players starting at position 1. The players are represented by different colors: Player 1 (cyan) and Player 2 (lime).
2. **Rolling the Dice**: Players take turns clicking the dice button to roll a number between 1 and 6.
3. **Moving the Piece**: The player's piece moves forward by the number rolled. If the piece lands on a ladder, it moves up to the top of the ladder. If it lands on a snake, it moves down to the snake's tail.
4. **Winning the Game**: The first player to reach square 100 wins the game. The game will display a message declaring the winner.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PrakEntech/SnakeAndLadder.git
   cd SnakeAndLadder
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required libraries:
   ```bash
   pip install pillow
   ```

3. **Run the Game**:
   ```bash
   python test.py
   ```

## Usage

- **Starting the Game**: When you run the `snake_and_ladder.py` script, the game window will open. Players take turns clicking the dice button to move their pieces on the board.
- **Game Rules**: The game follows the traditional rules of Snake and Ladder. Ladders will move you up, and snakes will bring you down. Rolling a 6 allows you to roll again.

## Code Overview

- **Tkinter**: Used to create the graphical user interface, including the game board, player pieces, and dice button.
- **Pillow**: Used to handle the image of the board.
- **Game Logic**: Handles player movement, snake and ladder interactions, and win conditions.

## Files

- **snake_and_ladder.py**: The main game file that contains all the game logic and GUI setup.
- **Board.png**: The image file used for the game board.

## Future Enhancements

- **Single Player Mode**: Add an AI opponent for solo play.
- **Custom Board**: Allow users to customize the board with their own snakes and ladders.
- **High Scores**: Track and display high scores or fastest wins.
