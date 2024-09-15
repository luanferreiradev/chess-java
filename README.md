# Chess Java Project

This project is a chess game system developed in Java, aimed at applying Object-Oriented Programming (OOP) concepts. The system simulates a chessboard where players can make moves and interact with the pieces, following standard chess rules.

## Features

- Implementation of a chessboard on an 8x8 matrix.
- Movement of pieces (rook, king, pawn, bishop, knight, and queen) with their specific rules.
- Alternating turns between two players.
- Validation of possible moves for each piece.
- Check and checkmate detection.
- Piece capture logic.
- Special moves like castling, en passant, and pawn promotion.

## Requirements

- Java 8 or higher.
- Your choice of IDE (IntelliJ IDEA, Eclipse, NetBeans, etc.).
- Git (for code versioning).

## How to Run the Project

1. Clone the repository from GitHub:
   ```bash
   git clone git@github.com:luanferreiradev/chess-java.git
2. Navigate to the project directory:
    ```bash
   cd chess-java
3. Compile and run the program:
- If you're using an IDE, just import the project and run the Program.java file located in src/Application/.
- If you prefer using the terminal, compile and run the program with the following commands:
    ```bash
    javac src/Application/Program.java
    java src/Application/Program
  
#Project Structure

src/ - Contains the project source code files.
 -Application/Program.java - The main class that runs the chess game.
 -Board/ - Classes responsible for the board and piece logic.
 -UI/ - Methods for displaying the board and game information to the player.

#Applied Concepts

This project applies several OOP concepts and good programming practices, including:

-Encapsulation: Class properties are protected and accessed via public methods.
-Inheritance and Polymorphism: The piece classes (e.g., Rook, King, Pawn) inherit from a base class ChessPiece.
-Exceptions: Error handling is managed through custom exceptions like BoardException and ChessException.
-Layered Pattern: Separation of game logic into different responsibility layers.

#Special Moves

In addition to standard piece movements, the system also supports special chess moves:

-Castling: A special move involving the king and one of the rooks.
-En Passant: A special pawn capture move.
-Pawn Promotion: When a pawn reaches the opposite side of the board, it can be promoted to another piece (usually a queen).

#Contributions

If you wish to contribute to this project, feel free to open issues or submit pull requests. All help is welcome!

#License

This project is licensed under the MIT License. See the LICENSE file for details.

    ```css
    This English version covers the same aspects as the original, including features, how to run the project, and the applied OOP concepts. You can modify it to fit specific project details if necessary.

