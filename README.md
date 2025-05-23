# Connect 4 with AI Opponent

This is a Python implementation of the classic Connect 4 game using Pygame, featuring an AI opponent that uses the Minimax algorithm with Alpha-Beta pruning.

## Key Features
- Player vs AI gameplay
- Graphical interface with smooth piece dropping animation
- AI using Minimax algorithm with depth 5
- Winning sequence highlight
- Random first turn selection

## Technical Details
- Built with Pygame for graphics
- Uses NumPy for board representation
- AI evaluation includes:
  - Horizontal, vertical, and diagonal win checks
  - Position scoring based on piece patterns
  - Center column preference
  - Defensive play against opponent threats

## Game Mechanics
- Standard 6x7 Connect 4 board
- Players alternate dropping pieces
- AI evaluates positions using heuristic scoring
- Winning sequences are highlighted in yellow
- Victory message displayed when game ends
