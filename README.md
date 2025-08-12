# 🎯 Hangman Word Guessing Game

A simple **Python terminal game** where the player guesses letters to find the hidden word before running out of turns.

## 📜 Description
This is a beginner-friendly game that demonstrates:
- Lists and `random.choice()` for word selection
- Loops (`while` and `for`)
- String operations for tracking guessed letters
- Conditional logic to check correct and incorrect guesses

You start with **12 turns**. Each wrong guess reduces the number of turns.  
Guess all letters correctly before your turns run out to win!

---

## 🚀 How to Run
1. Make sure you have **Python 3** installed.
2. Save the game code into a file named `hangman.py`.
3. Open a terminal or command prompt and run:
   ```bash
   python hangman.py
🕹 How to Play
The game will randomly select a secret word from a list.

You will see underscores _ representing the unguessed letters.

Enter one letter at a time to guess.

If your guess is correct, the letter appears in the word.

If your guess is wrong, your remaining turns decrease by 1.

The game ends when:

✅ You guess all letters (You Win 🎉)

❌ You run out of turns (You Lose 😢)

📂 Example Gameplay
less
Copy
Edit
What is your name? Suleman
Good Luck !  Suleman
Guess the characters
_
_
_
_
_
_
guess a character: p
Wrong
You have 11 more guesses
_
p
_
_
_
_
guess a character: y
p y _ _ _ _
...
🛠 Features
Random word selection from a list

12 wrong guesses allowed

Tracks all guessed letters

Win/lose messages

💡 Ideas for Improvement
Prevent repeated guesses from wasting turns.

Make input case-insensitive (treat "A" and "a" the same).

Display underscores and guessed letters on the same line for cleaner output.

Add difficulty levels with different turn limits.

Load words from a file for a bigger vocabulary.

📄 License
This project is free to use for learning purposes.

yaml
Copy
Edit
