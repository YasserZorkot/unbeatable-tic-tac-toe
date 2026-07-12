# Unbeatable Tic-Tac-Toe AI using Minimax

An implementation of Tic-Tac-Toe featuring an unbeatable artificial intelligence powered by the **Minimax algorithm**. The game includes a graphical user interface built with Tkinter, allowing players to compete against an AI that always chooses the optimal move.

---

# Project Overview

This project demonstrates the application of the Minimax algorithm in adversarial search. The AI explores every possible game state to determine the best move, ensuring that it can never be defeated. The project combines game theory, recursive search, and GUI development into a complete interactive application.

---

# Features

* Unbeatable AI using the Minimax algorithm
* Interactive graphical interface with Tkinter
* Human vs AI gameplay
* Automatic win and draw detection
* Automatic game reset after each match
* Optimal move selection through recursive search

---

# Technologies Used

* Python
* Tkinter

---

# Algorithm

The AI uses the **Minimax algorithm**, which recursively evaluates every possible game state.

* The human player (X) acts as the minimizing player.
* The AI (O) acts as the maximizing player.
* Terminal states are scored as:

  * AI Win = +1
  * Draw = 0
  * Human Win = -1

By exploring the complete game tree, the AI always selects the move with the highest possible outcome, making it impossible to defeat.

---

# Game Logic

The application implements:

* Win detection
* Draw detection
* Recursive Minimax search
* Best move selection
* Turn management
* Graphical board updates
* Game reset functionality

---

# Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/unbeatable-tic-tac-toe-ai.git
cd unbeatable-tic-tac-toe-ai
```

---

# Running the Application

Launch the game with:

```bash
python minimax_bot.py
```
