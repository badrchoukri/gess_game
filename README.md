Bash Guessing Game
A simple, interactive terminal game built with Bash. This script challenges users to guess the exact number of files located in the current working directory.

🚀 How It Works
The script calculates the total number of files in the folder using the ls and wc commands, then enters a loop that provides feedback—"Too high" or "Too low"—until the user provides the correct answer.

🛠️ Usage
To run this script on your local machine, follow these steps:

Clone the repository:

Bash
git clone https://github.com/YOUR_USERNAME/guessing-game.git
cd guessing-game
Grant execution permissions:

Bash
chmod +x guessing_game.sh
Run the game:

Bash
./guessing_game.sh
🧠 Logic Breakdown
The script utilizes several core shell scripting concepts:

Local Variables: Uses local scope for clean function execution.

Command Substitution: Captures file counts using $(ls -1 | wc -l).

Conditional Logic: Implements if/elif/else blocks to guide the user.

While Loops: Ensures the game continues until the condition (correct guess) is met.

📋 Requirements
A Unix-like environment (Linux, macOS, or WSL on Windows).

Bash shell.
