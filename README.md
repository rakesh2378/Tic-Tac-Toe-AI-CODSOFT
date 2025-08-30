# 🎮 Tic Tac Toe AI (with Pygame)

This project is a Tic Tac Toe game built using Python and Pygame, featuring a powerful AI opponent powered by the Minimax algorithm. You can play against another player (PvP mode) or challenge the computer in AI mode.

# ✨ Features

🧑‍🤝‍🧑 Two Game Modes:

PvP Mode – Play with a friend.

AI Mode – Challenge the computer (AI).

🧠 AI Difficulty Levels:

Level 0 (Easy) → AI makes random moves.

Level 1 (Hard) → AI uses the Minimax algorithm for optimal play.

🎨 Interactive GUI built with Pygame:

Draws X (cross) and O (circle).

Highlights winning combinations with colored lines.

🔄 Game Reset Option (Press R to restart).

🎛️ Switch Game Modes during play (G key).

# 🛠️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/tic-tac-toe-ai.git
cd tic-tac-toe-ai


Install dependencies:

pip install pygame numpy


Run the game:

python main.py

# 🎮 Controls

Mouse Click → Place your mark (X or O).

R → Reset the game.

G → Switch between PvP and AI modes.

0 → Set AI to Easy (random moves).

1 → Set AI to Hard (Minimax).

Close Window → Quit game.

# 🧩 How It Works

The game board is represented as a 3x3 NumPy array.

AI uses the Minimax algorithm to evaluate possible moves:

Maximizing player → Human

Minimizing player → AI

If AI is set to random mode, it picks moves randomly.

# 📸 Demo Screenshot


# 📂 Project Structure
├── constants.py      # Stores game constants (colors, board size, etc.)
├── main.py           # Main game logic & AI
├── README.md         # Project documentation

# 🚀 Future Improvements

Add sound effects 🎵

Add a scoreboard 🏆

Add GUI menu for difficulty selection

Improve animations for moves

# 👨‍💻 Author

Developed by Laxminarayana 💡
Feel free to contribute and enhance this project!


