# Quantum-Cipher AKA Elo Prime
The beginning of the world's greatest chess engine. . . . . This,once finished,will obliterate Stockfish like AlphaZero did years ago. . . . . . . 

## Overview

This project is a simple implementation of a chess engine written in C++. It includes basic functionalities such as move generation, game state evaluation, and support for the Universal Chess Interface (UCI) protocol.

## Current State

- **Move Generation:** The engine can generate legal moves for each piece based on their rules of movement.
- **UCI Support:** It follows the UCI protocol for communication with GUIs and other chess software.
- **Alpha-Beta Search:** The engine uses alpha-beta pruning for move search and evaluation.

## Approximate Rating

Considering the current implementation and basic functionalities, the engine may perform at a level comparable to beginner to intermediate human players, with an estimated rating of around 1000-1500 Elo.

## Areas for Improvement

- **Improved Evaluation Function:** Enhance the evaluation function to better assess the board state, considering factors like piece values, positional advantages, pawn structure, and king safety.
- **Search Algorithm Optimization:** Implement more advanced search algorithms such as iterative deepening, transposition tables, and quiescence search to improve move selection and depth.
- **Enhanced Move Generation:** Include special moves like castling, en passant, pawn promotion, and handle check, checkmate, and stalemate conditions.
- **Performance Optimization:** Optimize data structures and algorithms for faster move generation and evaluation, especially for deeper search depths.

## Future Plans

- **Advanced Algorithms:** Implement advanced algorithms like Monte Carlo Tree Search (MCTS) or neural network-based approaches for improved move selection and evaluation.
- **GUI Integration:** Develop a graphical user interface (GUI) for the engine to enable user-friendly interactions and gameplay.
- **Testing and Benchmarking:** Conduct thorough testing against established chess engines and human players to evaluate performance and rating accurately.
- **Documentation and User Guide:** Create detailed documentation and a user guide for the engine, including how to use it, its features, and customization options.

## Getting Started

To compile and run the chess engine, follow these steps:

1. Clone the repository to your local machine.
2. Compile the source code using a C++ compiler (e.g., g++).
3. Run the executable file to start the engine.
4. Connect the engine to a compatible chess GUI using the UCI protocol for gameplay.

## Contribution Guidelines

Contributions to the project are welcome! Follow these guidelines:

- Fork the repository and create a new branch for your changes.
- Make your modifications and ensure they adhere to coding standards and best practices.
- Write clear commit messages explaining the purpose of each change.
- Submit a pull request detailing your changes and improvements.

