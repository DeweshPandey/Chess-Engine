# Chess Engine

## Overview

Welcome to the Chess Engine project! This is a personal project dedicated to creating a comprehensive chess gaming experience using Python and Pygame. Our chess engine features a wide array of functionalities, including castling, en passant, and support for both single and multiplayer modes. Most notably, it incorporates the NegaMax algorithm with Alpha-Beta Pruning to create a formidable chessbot capable of achieving a rating of 1800 against Stockfish.

## Project Highlights

### Key Features

- **Chess Game Implementation:** We've developed a fully functional chess game with support for standard chess rules, including pawn promotion, castling, and en passant.

- **Single and Multiplayer Modes:** Whether you want to play against a friend or challenge the chessbot, our engine accommodates both single-player and two-player modes.

- **AI Chessbot:** The chessbot is powered by the NegaMax algorithm with Alpha-Beta Pruning, making it a formidable opponent with a competitive 1800 rating against Stockfish.

- **User-Friendly GUI:** Our Pygame-based graphical user interface provides an intuitive and visually appealing chess gaming experience.

- **Efficient Move Validation:** Robust move validation ensures that only legal moves are allowed, enhancing the authenticity of the game.

### NegaMax Algorithm and Alpha-Beta Pruning

Our chessbot's intelligence is achieved through the implementation of the NegaMax algorithm, a variant of the Minimax algorithm used in game theory. NegaMax is combined with the Alpha-Beta Pruning technique, which significantly reduces the number of nodes evaluated in the search tree. This combination allows our chessbot to efficiently explore potential moves and make optimal decisions.

### How to Play

1. **Clone the Repository:** Start by cloning this repository to your local machine using Git.

2. **Install Dependencies:** Make sure to install the required libraries and dependencies. You can find these details in the project's requirements file.

3. **Run the Game:** Execute the main Python script to launch the chess game with the user-friendly Pygame-based GUI.

4. **Game Modes:**
    - **Single Player:** Challenge the chessbot and experience its competitive AI.
    - **Multiplayer:** Play with a friend and enjoy a traditional chess game.

### Project Structure

- `src/`: This directory contains the source code for the chess engine, including the game logic, AI algorithms, and GUI implementation.

- `assets/`: All game-related assets, such as chess piece images and icons, are stored here.

- `docs/`: Documentation and additional resources related to the project can be found in this directory.

- `tests/`: Unit tests and test cases to ensure the reliability of the engine.


## License

This project is licensed under the MIT License. For full details, please refer to the [LICENSE.md](LICENSE.md) file in the repository.

We hope you enjoy playing and exploring our Chess Engine project as much as we enjoyed creating it!
 
