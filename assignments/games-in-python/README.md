
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

In this assignment, you will build a text-based Hangman game in Python. You will practice using strings, loops, conditionals, and user input to manage game state and player interaction.

## 📝 Tasks

### 🛠️	Build Core Game Loop

#### Description
Create the main game loop that runs Hangman from start to finish. The program should choose a random word and repeatedly ask the player for letter guesses until they win or run out of attempts.

#### Requirements
Completed program should:

- Randomly choose one word from a predefined list.
- Display the hidden word as underscores and update it as correct letters are guessed.
- Keep running turns until the whole word is guessed or attempts reach zero.
- Show a clear win or lose message at the end.


### 🛠️	Handle Input and Guess Tracking

#### Description
Add input validation and tracking so the game responds correctly to repeated, correct, and incorrect guesses.

#### Requirements
Completed program should:

- Accept one letter per guess and reject invalid input (empty, multiple characters, or non-letter values).
- Track letters already guessed and notify the player when a letter is repeated.
- Decrease remaining attempts only for new incorrect guesses.
- Show the current guessed word and remaining attempts after each valid turn.
