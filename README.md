# Hangman


This Python script implements a basic Hangman game where a player guesses letters to uncover a hidden word. The game proceeds as follows:

Initialization:

- A random word is selected from a list of words (word_list).
- The length of the chosen word is determined.
- The player starts with a set number of lives (6).

Game Setup:

- The initial display of the word is set up with underscores representing each letter.

Game Loop:

- The player is prompted to guess a letter.
- The console is cleared to refresh the display.
- If the guessed letter has already been guessed, a message is shown.
- For each position in the word, if the guessed letter matches, it updates the display with the correct letter.
- If the guessed letter is not in the word, a life is lost, and the number of remaining lives is displayed.
- The current state of the word is printed, showing correct guesses and remaining underscores.
- The game ends if there are no underscores left (the player wins) or if the player runs out of lives (the player loses).

End of Game:

- If the player wins, a victory message is displayed.
- If the player loses, the correct word is revealed, and a game-over message is displayed.
- The game utilizes ASCII art for visual feedback (stages) and a logo (logo), imported from hangman_art.
