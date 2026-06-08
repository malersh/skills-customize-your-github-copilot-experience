
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Hangman game using Python strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Word Selection and Setup

#### Description
Choose a secret word from a predefined list and initialize the game state before starting the loop.

#### Requirements
Completed program should:

- Randomly select one word from a predefined list of possible words
- Initialize `guessed_letters`, `incorrect_guesses`, and `max_incorrect`
- Prepare a display format that shows guessed letters and hidden letters as blanks

### 🛠️ Guess Processing Loop

#### Description
Implement the main game loop to accept letter guesses, update game state, and display progress.

#### Requirements
Completed program should:

- Prompt the player for a single letter guess each turn
- Reveal correctly guessed letters in the displayed word progress
- Track incorrect guesses and reduce remaining attempts accordingly
- Prevent repeated letter guesses from affecting the game state incorrectly

### 🛠️ Game Completion and Messages

#### Description
Finish the game with a win or lose result and display the secret word at the end.

#### Requirements
Completed program should:

- End when the word is fully guessed or when the player runs out of attempts
- Print a win message if the player guesses the word
- Print a lose message if the player uses all incorrect guesses
- Reveal the correct word when the game ends
