# Generate-Random-Number
# 🎲 Random Number Guessing Game

A simple Python script that generates a random number and prompts the user to guess it. The script provides feedback after each guess and continues until the user gets it right.

---

## 📋 Description

This script includes the following features:

- Generates a random number using Python’s built-in `random` module.
- Seeds the random number generator for reproducibility.
- Prompts the user to enter a guess and validates the input.
- Provides feedback on whether the guess is too high, too low, or correct.
- Continues looping until the correct number is guessed.
- Designed to run in a Python 3 environment.

---

## 🛠️ Requirements

- Python 3.x  
- No external libraries are needed.

---

## ▶️ Usage

1. Clone this repository or copy the script.
2. Save the script as `guessing_game.py`.
3. Open a terminal and navigate to the script's directory.
4. Run the script with:

```bash
python guessing_game.py

🧪 Example Output

Guess the number between 1 and 100:
> 50
Too high! Try again.
> 25
Too low! Try again.
> 37
Correct! You guessed the number!

**⚙️ Notes**

The random number generator uses a fixed seed for consistent results.
You can remove or modify the seed line to generate a new number each run.
Input is validated to prevent crashes due to invalid (non-numeric) entries.
The number range can be adjusted easily in the script.

**📄 License**

This project is licensed under the MIT License.
