# Word Guessing Game (Python)

A simple command-line word guessing game built in Python. The program randomly selects a word from a predefined list, and the player must guess the word one letter at a time before running out of attempts.

## Features

* Random word selection using Python's `random` module.
* Letter-by-letter guessing system.
* Tracks correct guesses and displays progress.
* Limited number of attempts to increase the challenge.
* Win and lose conditions with appropriate messages.

## How It Works

1. The program randomly chooses a word from the word bank.
2. The player enters one letter per turn.
3. If the guessed letter exists in the word, all matching positions are revealed.
4. If the guess is incorrect, the number of remaining attempts decreases.
5. The game ends when:

   * The player correctly guesses the entire word, or
   * All attempts are used up.

## Technologies Used

* Python 3
* Random Module

## Learning Objectives

This project demonstrates:

* Loops (`while`, `for`)
* Conditional statements (`if`, `else`)
* Lists and string manipulation
* User input handling
* Basic game logic implementation

A fun beginner-friendly project for practicing Python fundamentals and understanding how simple interactive games are built.
