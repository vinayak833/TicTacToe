# Tic Tac Toe Game

A simple Tic Tac Toe game built using HTML, CSS, and JavaScript. Two players can play alternately on the same device. The game automatically detects the winner and provides options to start a new game or reset the board.

---

## Features

- Two-player gameplay (X and O)
- Automatic winner detection
- Reset Game functionality
- New Game option after a winner is announced
- Responsive layout using Flexbox
- Simple and clean user interface

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

---

## Project Structure
"""
tic-tac-toe/
│── index.html
│── tic.css
│── tic.js
└── README.md
"""

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/tic-tac-toe.git
```

### Run the Project

Open the project folder and launch `index.html` in your preferred web browser.

---

## How to Play

1. The game starts with **Player O**.
2. Players take turns clicking on an empty box.
3. Once selected, a box cannot be clicked again.
4. The game checks for a winning combination after every move.
5. When a player wins, a message is displayed and the board is disabled.
6. Click **New Game** or **Reset Game** to start another match.

---

## Winning Combinations

The game checks the following winning patterns:

- Top row
- Middle row
- Bottom row
- Left column
- Middle column
- Right column
- Main diagonal
- Anti-diagonal

