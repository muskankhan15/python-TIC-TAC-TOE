#Tic-Tac-Toe Game (Pygame)

A simple graphical Tic-Tac-Toe (X-O) game built using Python and Pygame.
Players take turns clicking on the grid to place X and O, and the board updates in real time. This project is great for beginners learning event handling, rendering, and game loops in Pygame.

🚀 Features

🎮 Interactive 3×3 Tic-Tac-Toe grid

🖱️ Mouse-click based input

🔄 Turn switching between X and O

🖥️ Real-time board rendering

🎨 Clean UI created with lines, fonts, and colors

🚪 Exit easily by closing the game window

🧠 How It Works

Pygame initializes a 600×600 window.

The screen displays a Tic-Tac-Toe grid using draw lines.

Player turns alternate between X and O.

When the user clicks inside a cell, the corresponding symbol is drawn.

The game continues until the user closes the window (QUIT event).

Note: You currently have a small bug —
board[row][col] == player should be = not ==.
I can fix it if you want!

📂 Project Structure
.
├── xo_game.py
└── README.md

🛠 Requirements

Install Pygame:

pip install pygame

⭐ Future Improvements

Add win/draw detection

Add restart button

Add score tracking

Highlight winning line

Add sound effects

❤️ Support the Project

If you like this project, feel free to star ⭐ the repository!
