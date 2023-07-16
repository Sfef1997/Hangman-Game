# Hangman Game

This is a Hangman game implemented using HTML, CSS, and JavaScript. The game displays a set of dashes representing the letters of a word. The player's objective is to guess the word by clicking on the available letters. The game provides feedback on correct and incorrect guesses and ends when the player either guesses the word correctly or reaches the maximum number of wrong attempts.

## Game Setup

- The game loads a set of letters (including the alphabet and special characters) and displays them as clickable spans.
- A word is randomly chosen from a collection of words and categories provided in a JSON file.
- The chosen word is displayed as a set of empty spans, with each span representing a letter in the word.

## Gameplay

- The player can click on the available letters to guess the word.
- If the clicked letter matches any letter in the word, the corresponding empty span is filled with the correct letter.
- If the clicked letter does not match any letter in the word, a part of the hangman drawing is displayed, indicating a wrong attempt.
- The player can continue guessing until either the word is guessed correctly or the maximum number of wrong attempts is reached.
- When the game ends, a popup message is displayed, indicating whether the player won or lost. The actual word is revealed in case of a loss.
- The player can start a new game by clicking the "Start Game" button.

## Sound Effects

- The game includes sound effects for successful and failed attempts.
