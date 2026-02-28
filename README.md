# 🎮 Bash Guessing Game

A lightweight, interactive terminal-based game that challenges you to guess the number of files in your current directory. This project demonstrates core **Shell Scripting** concepts like loops, conditionals, and command substitution.

---

## ✨ Features
* **Real-time Logic:** Dynamically counts files every time the game starts.
* **Interactive Feedback:** Tells you if your guess is too high or too low.
* **Clean Code:** Uses local variables and functions for better script structure.

--- 

## 🚀 Getting Started

### Prerequisites
You'll need a Unix-like environment (Linux, macOS, or WSL on Windows) and the `bash` shell.

### Installation & Execution
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/guessing-game.git](https://github.com/YOUR_GITHUB_USERNAME/guessing-game.git)
   ```
2.**Make the script executable**:
   ```bash
   chmod +x guessing_game.sh
   ```
3. **Play the game**:
```bash
./guessing_game.sh
```
---

## 🛠️ Built With

* **Bash** - The Bourne Again SHell.
* **ls & wc** - Standard Unix utilities for directory listing and word/line counting.

## 🧠 Logic Preview
The core engine of the game uses a while loop to keep the game alive until you win:

```bash
while [[ $guess -ne $num_files ]]; do
    read -p "Enter your guess: " guess
    # Logic checks go here...
done
```
