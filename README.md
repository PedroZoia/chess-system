# Chess System Java ♟️

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

This is a complete chess game system project, developed in **Java**. The game runs directly in the terminal and was built to demonstrate the practical application of advanced Object-Oriented Programming (OOP) concepts.

## 🚀 Features

- **Official Rules:** Full implementation of movement logic for all pieces.
- **Special Moves:**
  - 🏰 **Castling**
  - ♟️ **En Passant**
  - ♜ **Pawn Promotion**
- **Game System:**
  - Turn control (White vs. Black).
  - Captured pieces list.
  - Colored highlighting of possible moves on the board.
  - Automatic detection of **Check** and **Checkmate**.
- **Error Handling:** Custom exception system for invalid moves.

## 🛠️ Applied OOP Concepts

The project uses a layered architecture to separate board logic from specific chess logic:
- **Encapsulation:** Protection of the internal states of pieces and the board.
- **Inheritance and Polymorphism:** Each piece has its specific behavior inheriting from a base class.
- **Abstract Classes:** Definition of templates for pieces and movements.
- **Composition:** The board is composed of a matrix of pieces.

## 💻 How to Run

### Prerequisites
- **Java JDK** (version 11 or higher).
- A terminal that supports ANSI colors (Git Bash, VS Code Terminal, Linux/Mac Terminal).

### Instructions
**Clone this repository:**
```bash
git clone [https://github.com/PedroZoia/chess-system.git](https://github.com/PedroZoia/chess-system.git)
   ```
2. Enter the project folder:
```
  cd chess-system
```
3. Compile the project:
```
  javac application/Program.java
```
4.Run the game:
```
  java application/Program
```
## 🎮 How to Play:

- The game uses the standard algebraic notation system (column + row).
- On your turn, type the position of the piece you want to move (e.g., c2).
- The system will highlight the fields where that piece can move.
- Type the destination position (e.g., c4).
- The game ends when one player applies Checkmate.
