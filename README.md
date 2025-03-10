# Chess Solver

![GitHub release (latest by date)](https://img.shields.io/github/v/release/Quinntana/Chess_solver)
![GitHub license](https://img.shields.io/github/license/Quinntana/Chess_solver)
![GitHub stars](https://img.shields.io/github/stars/Quinntana/Chess_solver)

This repository automates capturing and analyzing a live chessboard. It identifies piece positions from a screenshot, generates FEN notation, and provides best moves using a chess engine.

## Files Overview
- **main.py**: Entry point for capturing, cropping, and analyzing the board.  
- **crop.py**: Captures a screenshot and crops the chessboard region.  
- **grid.py**: Splits the cropped board into individual squares.  
- **recognise.py**: Uses templates to identify each piece from cropped squares.  
- **fen.py**: Builds a FEN string based on recognized pieces.  
- **engine.py**: Interfaces with the Stockfish engine to analyze positions.

## Demo
https://www.youtube.com/watch?v=EQkozOIHkus

## Usage
1. Install dependencies (e.g., `python-chess`, `opencv-python`, `pyautogui`, `pyperclip`).
   ```bash
   pip install -r requirements.txt
3. Run:
   ```bash
   python main.py
