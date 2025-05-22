# ⚫⚪ Reversi / Othello

[![Language](https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Platform](https://img.shields.io/badge/Platform-Terminal%20(Console)-333333?style=for-the-badge)]()
[![Graphics](https://img.shields.io/badge/Graphics-ASCII%20Grid-8B008B?style=for-the-badge)]()
[![Input](https://img.shields.io/badge/Input-Keyboard-556B2F?style=for-the-badge)]()

This project is a command-line implementation of **Reversi (Othello)** built in **C**, featuring full game mechanics, a computer AI opponent, and a text-based UI. The board logic is built using 2D arrays, and the computer’s move selection is optimized based on a **max-flip scoring algorithm**.

The player selects a color (Black or White), and the game proceeds turn-by-turn until the board is full or no valid moves remain.

---

## 🎮 Features

- **Standard Reversi Gameplay**
  - Board size: dynamic (`n x n`, even, max 26)
  - Real-time board updates after each move

- **Valid Move Detection**
  - Uses directional checks across all 8 directions
  - Ensures legality of player and AI moves

- **Computer AI**
  - Chooses moves that flip the most tiles using a score matrix
  - Simple but effective max-flip strategy

- **Game End Detection**
  - Ends when no more legal moves exist or an invalid move is made

---

## 🧠 Technical Overview

- **Language**: C
- **Input**: Console (e.g., `d3`, `f5`)
- **Board Representation**: 2D `char` array (`U`, `B`, `W`)
- **AI Logic**:
  - Scans the board and scores legal moves
  - Chooses the move that maximizes immediate tile flips


---
