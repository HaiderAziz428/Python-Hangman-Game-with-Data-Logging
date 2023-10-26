# Python-Hangman-Game-with-Data-Logging

## Overview

This is a simple Hangman game implemented in Python. The game allows players to guess a word within a limited number of attempts. The program also logs player data, such as their name and game outcome (win or lose), to an Excel file for future reference.

## Prerequisites

Before running the game, make sure you have the following dependencies installed:
- Python 3
- openpyxl library (for Excel data logging)

## Features 

Classic Hangman word-guessing gameplay.
Data logging of player names and game outcomes.
Fun hangman figure graphics as you make incorrect guesses.
Easy-to-use interface for entering guesses.

## Usage

Run the Python script (hangman.py).
Enter a player name when prompted.
You will have 10 attempts to guess the word.
Enter a single letter as your guess. If the input is not a valid character, you will be asked to enter a valid character.
The game will provide feedback on the number of turns left and display a hangman figure as you make incorrect guesses.
If you guess the word correctly, you win the game. Your name and "Congratulation! You won" will be logged in the Excel file.
If you run out of attempts, you lose the game. Your name and "you lose" will be logged in the Excel file.
After the game, you will be asked if you want to play again. Enter 'y' to play again or 'n' to exit.

## Data Logging

Player data, including their name and game outcome, is logged to an Excel file named data.xlsx. The Excel file will be created in the same directory as the script if it doesn't already exist.

## Project Structure

The project files are organized as follows:

hangman.py: The main Python script for the Hangman game.
data.xlsx: The Excel file for logging player data.
README.md: This documentation file.
