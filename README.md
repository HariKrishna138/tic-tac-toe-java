# tic-tac-toe-java
Command-line Tic Tac Toe game in Java
# 🎮 Tic Tac Toe Game — Java Console Application

A **Java-based command-line Tic Tac Toe game** designed for two players.  
The application includes **robust input validation, win/draw detection, replay support, and score tracking across multiple rounds**.

---

## 📘 Project Description

This project implements a **classic 3×3 Tic Tac Toe game** playable in the terminal.  
Players alternately place **X** or **O** by entering row and column numbers between **0 and 2**.

The game ensures:
- Only valid inputs are accepted
- Already occupied cells cannot be overwritten
- Wins and draws are detected automatically
- Players can replay without restarting the application
- Scores are maintained until the program exits

---

## 🖥️ Sample Console Output

=================================
        TIC TAC TOE GAME
=================================
Instructions:
- Two players take turns (X and O)
- Enter row and column values (0–2)
- First player to align three symbols wins
- Example input: 1 2
=================================

Enter Player X name: player1
Enter Player O name: player2

Current Board:
  0   1   2
0   |   |
  ---------
1   |   |
  ---------
2   |   |

player1's turn (X)
Enter row (0-2): 0
Enter column (0-2): 0

Current Board:
  0   1   2
0 X |   |
  ---------
1   |   |
  ---------
2   |   |
✨ Key Features
🎮 Gameplay

->Two-player mode (X vs O)

->Custom player names

->Turn-based gameplay

->Clear board display with row & column indices

->Replay option after each completed game

🧠 Logic & Validation

->Winner detection for rows, columns, and diagonals

->Automatic draw detection when the board is full

->Prevents invalid row/column input

->Prevents selecting already occupied cells

->Tracks scores across multiple rounds

🔄 Game Flow

Start Game
   ↓
Display Instructions
   ↓
Enter Player Names
   ↓
Initialize Empty Board
   ↓
Player X Turn
   ↓
Validate Input
   ↓
Place Symbol
   ↓
Check Win / Draw
   ↓
Switch Player
   ↓
Repeat Until Game Ends

🛠️ How to Run the Program
✅ Requirements

->Java JDK 8 or higher

▶️ Compile and Run

=>javac TicTacToeGame.java
=>java TicTacToeGame

🛠️ How to Run the Program
✅ Requirements

Java JDK 8 or higher

▶️ Compile and Run
javac TicTacToeGame.java
java TicTacToeGame

🕹️ How to Play
Board Layout
  0   1   2
0   |   |
  ---------
1   |   |
  ---------
2   |   |

Input Format

Enter row number (0–2)

Enter column number (0–2)

Example:

Enter row (0-2): 1
Enter column (0-2): 2

🏆 Win Conditions

A player wins by placing three identical symbols in:

Any row

Any column

Either diagonal

🤝 Draw Condition

If all 9 cells are filled and no winner is detected, the game ends in a draw.

📊 Score Tracking

Scores are preserved until the program terminates.

=>Final Scores:
  player1 (X): 2
  player2 (O): 1
