# 🎮 Hangman Game in Python
This is a simple command-line Hangman game built in Python. The player has to guess a hidden word by suggesting letters one at a time. The game ends when the player either successfully guesses the word or runs out of attempts.

## 📂 Files
- `words.txt`: Contains a list of words (one per line) that the game randomly selects from.

- `stages.txt`: Contains the ASCII art for each stage of the Hangman, separated by ###.

## 🧠 Features
- Random word selection from file.

- Clean ASCII-based hangman graphics.

- Validates user input (only single alphabetic characters).

- Tracks guessed letters and prevents duplicate guesses.

- Game over and success messages.

## 🔧 How to Run
1. Make sure `words.txt` and `stages.txt` are in the same directory.

2. Run the script using Python:

       python hangman.py
