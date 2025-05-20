
# 🧠 Gomoku Game Solver 🎮

A Python-based Gomoku (Five in a Row) game solver with **AI vs Human** and **AI vs AI** gameplay, featuring a strategic battle between the **Minimax** and **Alpha-Beta Pruning** algorithms — complete with a clean, interactive **GUI**.

---

## 🎯 Game Overview

Gomoku is a classic board game where two players take turns placing stones on a grid, aiming to get **five in a row** horizontally, vertically, or diagonally.

This project consists of two main modes:
- 👤 **Human vs. AI** – Play against a smart AI that uses the **Minimax algorithm**.
- 🤖 **AI vs. AI** – Watch an automated match between **Minimax** and **Alpha-Beta Pruning** algorithms.

---

## 🧩 Key Features

✅ Dynamic game engine for Gomoku rules  
✅ Minimax algorithm for strategic decision-making  
✅ Alpha-Beta pruning for optimized performance  
✅ AI vs AI simulation mode  
✅ Interactive GUI built in Python  
✅ Custom board size (e.g., 15x15, 19x19)  
✅ Updated board display after each move  
✅ Input-based or GUI-based gameplay  

---

## 🛠️ Project Components

### 🎮 Game Engine
- Parses and validates the current Gomoku board state
- Generates legal moves based on game rules
- Applies AI algorithms (Minimax or Alpha-Beta Pruning)
- Returns and displays the chosen move
- Supports depth-limited search to control complexity

### 🧠 AI Algorithms
- **Minimax**: Basic adversarial search for two-player games.
- **Alpha-Beta Pruning**: Enhanced Minimax with pruning to reduce search space.

---

## 🗂️ Knowledge Applied

- Minimax Algorithm  
- Alpha-Beta Pruning  
- Turn-based board game logic  
- GUI Development in Python (e.g., Tkinter or Pygame)

---

## 📥 Input & 📤 Output

### 📥 Input
- Current game board state (via GUI or console)
- Game mode selection (Human vs AI, AI vs AI)

### 📤 Output
- Coordinates of the AI’s chosen move
- Updated visual board display after each turn

---

## 🎨 GUI Preview

A bonus feature! We’ve developed a simple, user-friendly **GUI** for an enhanced experience.  
Players can click to place their stones, see AI responses in real time, and switch between game modes.

---

## 🧑‍💻 Team Contributions

This project was built as a team effort. We collaborated on algorithm design, GUI implementation, and game logic integration.
Jana Abdallah
Malak Sherif
Afnan Sayed 
Afnan Abdulkareem

---

## 📌 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/gomoku-solver.git
cd gomoku-solver

# Run the main script
python main.py
# Gomoku Game Solver
