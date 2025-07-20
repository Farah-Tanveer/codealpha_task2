# 🎯 Hangman Game (Python)

This is a simple **text-based Hangman game** developed in Python as part of my internship at **Code Alpha** under the Python programming domain.

The game randomly selects a word from a small list, and the player has to guess the word one letter at a time. The player is allowed a maximum of 6 incorrect guesses.

---

## 🧠 Features

- Predefined list of 5 random words
- Case-insensitive letter guessing
- Tracks and displays guessed letters
- Allows up to 6 incorrect attempts
- Fully text-based (console) game
- Clean and beginner-friendly code

---

## 🛠️ Technologies Used

- **Python 3.x**
- Standard libraries:
  - `random` for selecting words
  - `input()` and `print()` for interaction

---

## 📸 Example Gameplay

```plaintext
🎯 Welcome to Hangman!
Guess the word, one letter at a time.
You have 6 chances. Good luck!

Word: _ _ _ _ _
Guessed letters:
Remaining attempts: 6
Enter a letter: a
✅ Good guess!

...
🎉 Congratulations! You guessed the word: apple
