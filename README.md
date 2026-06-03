# python-number-guessing-game
A terminal-based Number Guessing Game built with Python, featuring pseudo-random number generation, loop control, and robust user input validation.

# 🎲 Number Guessing Game (Python)

A clean, terminal-based mini-game developed in Python that challenges users to guess a randomly generated integer within a limited number of attempts. This project demonstrates core programming concepts, error handling, and conditional control flows.

## 🎯 Project Features & Logic
* **Random Number Generation:** Generates a pseudo-random integer between 1 and 20 using Python's built-in `random` module.
* **Input Validation & Exception Handling:** Implements a `try-except` block to intercept `ValueError` exceptions, ensuring the application handles non-integer inputs gracefully without crashing.
* **Attempt Control System:** Limits the player to 3 operational attempts, dynamically updating and displaying the remaining retries after each incorrect guess.
* **State Management:** Uses conditional statements (`if-else`) to evaluate user guesses and breaks the execution loop instantly upon a successful match.

## 🛠 Technologies
* **Language:** Python 3.x
* **Core Modules:** `random`
* **Concepts Used:** While Loops, Exception Handling (`try/except`), Standard I/O, Formatted Strings (f-strings).
