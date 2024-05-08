# PhraseofFortuneGame

## Description
Phrase of Fortune is a Python GUI game inspired by the Wheel of Fortune built with Tkinter. It allows two players to compete against each other by guessing phrases related to different topics. The game features multiple rounds where players attempt to guess the hidden phrase by entering letters. Each correct guess reveals the letters in the phrase, while incorrect guesses result in a deduction of attempts. The player who correctly guesses the phrase or has the most wins at the end of the game wins the match.

## Features
- Interactive GUI built with Tkinter.
- Two-player gameplay with alternating rounds.
- Players can choose letters to guess the hidden phrase.
- Display of attempts left and wrong guesses.
- Random selection of phrases from predefined topics.
- Rematch option after the game ends.

## Usage
1. Ensure you have Python installed along with the required libraries: tkinter, openpyxl, random.
2. Prepare a list of phrases related to different topics in an Excel file (`listofphrases.xlsx`), with each row representing a topic and its associated phrases.
3. Run the Python script (`phrase_of_fortune.py`).
4. The game window will open with separate frames for each player.
5. Players take turns guessing phrases by entering letters in the provided input field.
6. If a player correctly guesses the phrase or runs out of attempts, the round ends, and the other player gets a chance to play.
7. The player with the most wins at the end of the game wins the match.
8. Players can choose to rematch after the game ends.

## Files
- `phrase_of_fortune.py`: The main Python script for running the game and handling player interactions.
- `listofphrases.xlsx`: An Excel file containing a list of phrases related to different topics.
- `README.md`: This file providing information about the game and usage instructions.

## Dependencies
- `tkinter`: Python's standard GUI toolkit for creating graphical user interfaces.
- `openpyxl`: A Python library for reading and writing Excel files.
- `random`: A Python module for generating random numbers and making random selections.

## Notes
- Ensure the `listofphrases.xlsx` file exists and is properly formatted with topics and phrases before running the game.
- Players can only guess letters; guessing entire phrases is not allowed.
- The game provides feedback on attempts left, wrong guesses, and wins.
- The game ends when a player correctly guesses the phrase or runs out of attempts.

## Credits
- Inspired by classic word guessing games and game show formats like "Wheel of Fortune." Built as a group project.

