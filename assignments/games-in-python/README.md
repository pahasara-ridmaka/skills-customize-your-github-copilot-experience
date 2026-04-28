
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a command-line Hangman game in Python that uses strings, conditionals, loops, and user input to let a player guess a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Task 1 — Core Game
#### Description
Implement the Hangman game loop that:
- chooses a random word,
- accepts single-letter guesses,
- shows progress (e.g., _ a _ g _ a _),
- tracks guessed letters and remaining attempts,
- ends when the word is guessed or attempts are exhausted.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Accept letter input (case-insensitive) and ignore repeated guesses.
- Display current progress and list of incorrect guesses.
- Track and display remaining attempts.
- Show a clear win or lose message and reveal the word on loss.


### 🛠️ Task 2 — Persistence & I/O
#### Description
Make the word list easy to maintain and optionally loadable from a file.

#### Requirements
- Word list may be stored in a Python list or a plain text file.
- If using a file, handle file-not-found errors with a friendly message.


### 🛠️ Task 3 — Stretch Goals (optional)
- Add difficulty levels that adjust allowed attempts or word length.
- Allow whole-word guesses.
- Save player high scores (wins / losses) to a small JSON file.
- Add ASCII-art hangman stages for visual feedback.

## 📚 Learning Outcomes
- Use and manipulate strings and lists.
- Design game loops and state tracking.
- Read/write simple files and handle basic errors.
- Implement input validation and user-friendly messages.

## 🔧 Starter Files
- [assignments/games-in-python/starter-code.py](assignments/games-in-python/starter-code.py) — minimal starter scaffold.

## ▶️ How to Run
- Run with Python 3:
	python3 assignments/games-in-python/starter-code.py

## ✅ Assessment Criteria
- Program meets all core requirements.
- Code is readable and modular (functions for major steps).
- Handles invalid input without crashing.
- (Optional) One or more stretch goals implemented.

## 💡 Hints
- Use `random.choice()` for selecting words.
- Track guessed letters in two sets: correct and incorrect.
- Show progress by joining characters, replacing unguessed letters with `_`.

