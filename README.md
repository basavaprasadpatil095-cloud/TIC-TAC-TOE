🎮 Tic Tac Toe Game (HTML, CSS, JavaScript)

A simple, interactive, and fully responsive Tic Tac Toe game built using core web technologies: HTML, CSS, and JavaScript. This project demonstrates fundamental front-end development concepts such as DOM manipulation, event handling, game logic implementation, and responsive UI design.

📌 Project Overview

This project is a classic 2-player Tic Tac Toe game where players take turns marking X and O on a 3×3 grid. The first player to align three marks horizontally, vertically, or diagonally wins the game. If all cells are filled without a winner, the game ends in a draw.

🚀 Features:

🎯 Two-player gameplay (X vs O)
🔄 Automatic player switching after each move
🏆 Winner detection (rows, columns, diagonals)
🤝 Draw detection when board is full
🔁 Reset button to restart the game anytime
🎨 Clean and modern UI design
💡 Responsive and beginner-friendly structure
⚡ Fast and lightweight (no frameworks used)
🧠 Game Logic Highlights

The board is represented using a JavaScript array of 9 elements
Each cell corresponds to an index from 0 to 8
Winning combinations are pre-defined using an array of index patterns:
Rows: [0,1,2], [3,4,5], [6,7,8]
Columns: [0,3,6], [1,4,7], [2,5,8]
Diagonals: [0,4,8], [2,4,6]
After each move:
The game checks for a winner
If no winner, it checks for a draw
Otherwise, it switches players

🛠️ Technologies Used:

HTML5 – Structure of the game board
CSS3 – Styling, layout, and hover effects
JavaScript (ES6) – Game logic and interactivity


🎮 How to Play:

Open the index.html file in any modern browser.
Player X starts first.
Click on any empty cell to place your mark.
Players alternate turns automatically.
First player to align 3 marks wins!
Click Reset Game to restart anytime.

"Developed as a learning project to practice front-end development fundamentals using vanilla JavaScript.
This project is open-source and free to use for learning and personal projects."
