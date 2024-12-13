# Connect4 AI Game

A Python implementation of the Connect4 game, featuring a minimax algorithm with alpha-beta pruning for AI moves. The game is built using Pygame for the graphical interface.

## Features
- Two-player mode: Human vs AI
- AI uses the minimax algorithm for optimal moves
- Real-time graphical board updates using Pygame
- Win detection for horizontal, vertical, and diagonal conditions

## Requirements
- Python 3.7+
- Pygame
- NumPy

## How to Run
1. Clone the repository:
    ```
    git clone https://github.com/yourusername/connect4-ai-game.git
    cd connect4-ai-game
    ```
2. Install the required dependencies:
    ```
    pip install pygame numpy
    ```
3. Run the game:
    ```
    python connect4_ai.py
    ```

## Game Controls
- **Mouse Movement:** Hover to select the column for your move.
- **Mouse Click:** Place your piece in the selected column.

## Code Highlights
- **Minimax Algorithm:** Ensures that the AI plays optimally.
- **Dynamic Scoring:** Uses heuristics for the AI to evaluate board states.
- **Real-time UI:** Interactive gameplay with a smooth graphical interface.

