# guessing-number# 🎮 Guess the Number Game

## 📌 Concept
This project is a simple Python-based game where the computer randomly selects a number between 1 and 10, and the user has to guess the correct number.

It is designed for beginners to understand basic programming concepts like user input, conditional statements, and random number generation.

---

## 💡 How It Works
- The system generates a random number
- The user enters a number as a guess
- If the guess matches the number → "Correct!"
- If not → "Wrong! Number was X"

---

## 🧠 Concepts Used
- Python Basics
- `random` module
- User Input (`input()`)
- Conditional Statements (`if-else`)

---

## 💻 Code

```python
import random

number = random.randint(1, 10)
guess = int(input("Guess a number (1-10): "))

if guess == number:
    print("Correct!")
else:
    print("Wrong! Number was", number)
```

---

## ▶️ How to Run
1. Install Python
2. Open in VS Code
3. Run:
   ```
   python guessing_number_game.py
   ```

---

## 🎯 Purpose
This project helps beginners practice Python fundamentals in a fun and interactive way.

---

## 🔗 GitHub Link
https://github.com/nagubadiudayalakssme-ux/guessing-number
