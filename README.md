# 🎯 Hangman Game

A classic word-guessing game built in Python. Uncover the secret word one letter at a time — before you run out of lives!

---

## 📖 About

This is a terminal-based Hangman game where the computer picks a random secret word and the player guesses letters one at a time. Words are categorized by length into three difficulty levels, each with a different number of lives.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- A `Words.txt` file in the same directory as the script (one word per line)

### Running the Game

```bash
python hangman.py
```

---

## 🎮 How to Play

1. Run the script and press `Y` when prompted to start.
2. Choose a difficulty level: **Easy**, **Medium**, or **Hard**.
3. The game will reveal how many letters are in the secret word using underscores (e.g., `_ _ _ _ _`).
4. Guess one letter at a time.
   - ✅ Correct guess — the letter is revealed in its position(s).
   - ❌ Wrong guess — you lose a life.
5. Win by uncovering the full word before your lives run out!
6. After each round, choose to play again or exit.

---

## 🏆 Difficulty Levels

| Level  | Word Length | Lives |
|--------|-------------|-------|
| Easy   | < 5 letters | 5     |
| Medium | 5–6 letters | 3     |
| Hard   | 7+ letters  | 4     |

---

## 📁 Project Structure

```
hangman/
├── hangman.py   # Main game script
└── Words.txt    # Word bank (one word per line)
```

---

## ✏️ Words.txt Format

The word list should be a plain text file with one word per line:

```
cat
dog
python
keyboard
...
```

---

## 🛠️ Features

- Three difficulty levels with words sorted by length
- Case-insensitive letter guessing
- Live feedback on remaining lives
- Play again option after each round

---

## 📝 Notes

- Guesses are **not** case-sensitive — `A` and `a` are treated the same.
- The game does not currently track previously guessed letters, so guessing the same letter twice will count as a new guess.

---
