# Tic-Tac-Toe-Game
🎮 Tic Tac Toe Game (Java Swing)

A simple Tic Tac Toe game built using Java Swing GUI. This is a two-player desktop application where players can enter their names and play the classic game with an interactive interface.

📌 Features
🧑‍🤝‍🧑 Two-player mode (Player X vs Player O)
🎨 Simple and clean GUI using Java Swing
🔄 Turn indicator display
🏆 Automatic winner detection
🤝 Draw detection
🔁 Game resets automatically after win/draw
🚫 Prevents overwriting already filled cells
🖥️ Screens
Player Input Screen
Enter Player X and Player O names
Click Start to begin
Game Board
3x3 grid
Displays current player's turn
Shows result popup on win/draw
🛠️ Technologies Used
Java
Swing (GUI)
AWT (Layout Management)
🚀 How to Run
1. Compile the Program
javac TicTacToeGame.java
2. Run the Program
java TicTacToeGame
🎯 How to Play
Enter names for both players
Click Start
Players take turns:
Player X starts first
Click on any empty cell to place your mark
The game ends when:
A player gets 3 in a row (win 🎉)
All cells are filled (draw 😃)
🧠 Game Logic
The board is a 3x3 grid of buttons
Each move:
Updates button text (X or O)
Switches turn
After every move:
Checks:
Rows
Columns
Diagonals
If no winner and board is full → Draw
🔁 Game Flow
Start Game → Enter Names → Play Turns → Check Winner/Draw → Show Result → Reset Game
📂 Project Structure
TicTacToeGame.java   # Main game file with GUI and logic
⚠️ Validation
Ensures both player names are entered before starting
Prevents clicking on already selected cells
👨‍💻 Author

Vishal Yadav

🌟 Future Improvements
🤖 Add AI (Single Player Mode)
🎨 Improve UI design
🔊 Add sound effects
📊 Score tracking system
