# Console Chess Game

This project is a console-based chess game developed in C# using the .NET platform.  
It implements the core rules of chess with a strong focus on object-oriented programming concepts such as inheritance, polymorphism, encapsulation, and exception handling.

The application runs entirely in the terminal and allows two players to play a complete chess match turn by turn.

## Features

- Console-based chessboard rendering
- Turn-based gameplay for two players
- Piece-specific movement rules
- Capture mechanics
- Check and checkmate validation
- Illegal move prevention
- Clear separation of responsibilities using OOP principles
- Custom exceptions for game and board validation

## Technologies

- Language: C#
- Platform: .NET (Console Application)
- Paradigm: Object-Oriented Programming

## Project Structure

The project is organized into well-defined namespaces and classes:

- **Program.cs**  
  Entry point of the application.

- **tabuleiro**  
  Core board logic and abstractions:
  - Board representation
  - Positions
  - Base piece class
  - Board-related exceptions

- **xadrez**  
  Chess-specific logic:
  - Individual piece classes (King, Queen, Rook, Bishop, Knight, Pawn)
  - Chess match controller
  - Chess position translation

- **Tela.cs**  
  Responsible for rendering the board and game information in the console.

This structure improves readability, maintainability, and makes the project suitable for academic evaluation.

## How to Run the Project

### Requirements
- .NET SDK installed (compatible with console applications)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/xadrez-console.git


   Navigate to the project directory:
   cd xadrez-console/xadrez-console


### Run the application:
  dotnet run
## How to Play

- The game starts with White's turn
- Players enter moves via console input using chess coordinates
- The system validates moves according to chess rules
- The game continues until a checkmate condition is reached
## Academic Purpose
This project was developed for educational purposes and demonstrates:

- Practical use of object-oriented programming in C#
- Class hierarchies and inheritance
- Polymorphism through chess piece behavior
- Exception handling for game rule enforcement
- Separation of concerns in a console application

## Possible Improvements

- Pawn promotion choice  
- Castling implementation  
- En passant support  
- Improved console visualization  
- Single-player mode with AI  
- Automated tests for game rules  

## Author

**Henrique**  
Student at **FATEC Americana**  
Degree in **Analysis and Systems Development**
