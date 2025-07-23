#♟️ Chess System

A console-based chess game developed in Java. This project demonstrates object-oriented programming (OOP) principles through the implementation of a complete chess game, including piece movement rules, game state management, and a simple text-based interface.
This project was made through Nelio Alves's Udemy Course "Java COMPLETO Programação Orientada a Objetos + Projetos"  @acenelio (Github)

##🧰 Features

- Full chess match simulation
- Move validation according to official chess rules
- Check and checkmate detection
- Object-oriented architecture
- Console-based UI with colored board representation
- Custom exceptions for error handling

##📁 Project Structure
```
chess-system/
├── src/
│ ├── application/
│ │ ├── Program.java # Main class
│ │ └── UI.java # Console-based UI
│ ├── boardgame/
│ │ ├── Board.java # Generic game board
│ │ ├── Piece.java # Base class for pieces
│ │ ├── Position.java # Coordinates system
│ │ └── BoardException.java
│ └── chess/
│ ├── ChessMatch.java # Game logic
│ ├── ChessPiece.java # Chess-specific pieces
│ ├── ChessPosition.java
│ ├── pieces/ # Individual chess piece classes
│ └── Color.java # Enum for piece colors
```
##🖥️ How to Run

1. **Requirements**:
   - Java JDK 8 or higher
   - Any IDE (e.g., Eclipse, IntelliJ) or command-line terminal

2. **Steps**:
   - Clone or download this repository
   - Open the project in your IDE or compile manually using:
     ```bash
     javac src/application/Program.java
     java application.Program
     ```

##🎮 Example Gameplay

After running, the console will show a chessboard. Players will be prompted to input their moves using standard algebraic notation (e.g., `e2` to `e4`). The game alternates turns and shows the updated board after each move.

##🎯 Learning Objectives

This project was developed as part of an OOP learning path. It demonstrates:

- Inheritance and polymorphism
- Encapsulation and abstraction
- Modular programming
- Exception handling
- Clean architecture practices

##📄 License

This project is for educational use and is not intended for production. Feel free to use it as a learning resource.

