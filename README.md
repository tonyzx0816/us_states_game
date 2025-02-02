# U.S. States Game

This project is a simple game built using Python's `turtle` and `pandas` libraries.  The game challenges the user to correctly name all 50 U.S. states.  It displays a blank map of the U.S. and prompts the user to enter state names. Correctly guessed states are displayed on the map.  The game keeps track of the number of correct guesses.  If the user types "Exit", the game ends, and a CSV file ("states_to_learn.csv") is generated containing the list of states the user did not guess correctly.

## Features

*   Interactive gameplay using the `turtle` graphics library.
*   Keeps track of your score (number of correctly guessed states).
*   Provides visual feedback by placing state names on the map.
*   Saves a list of missed states to a CSV file (`states_to_learn.csv`).
*   Case-insensitive input for state names.
