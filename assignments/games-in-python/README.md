
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a Hangman game using Python strings, loops, conditionals, random selection, and user input. Practice tracking game state and displaying an interactive game experience.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Create the variables needed to select a secret word and track the player's guesses.

#### Requirements
Completed program should:

- Use `random.choice()` to select a secret word from a predefined list.
- Initialize a collection to store correctly guessed letters.
- Initialize a counter or collection to track incorrect guesses.
- Set a maximum number of incorrect guesses.

### 🛠️ Implement the Guessing Loop

#### Description
Prompt the player for letter guesses and update the displayed word and remaining attempts after each guess.

#### Requirements
Completed program should:

- Continue prompting for guesses until the game ends.
- Accept a letter from the player using `input()`.
- Display the secret word's progress using underscores for unguessed letters, such as `_ y t _ o n`.
- Add a correct guess to the collection of guessed letters.
- Reduce or track incorrect guesses only when the letter is not in the secret word.
- Prevent the game loop from continuing after a win or loss.

### 🛠️ Handle the Game Result

#### Description
Finish the game by identifying whether the player won or lost and displaying a clear result message.

#### Requirements
Completed program should:

- Display a win message when every letter in the secret word has been guessed.
- Display a lose message when the maximum number of incorrect guesses is reached.
- Include the secret word in the lose message.
