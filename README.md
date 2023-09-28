# hangman

## Overview

Welcome to the Hangman Game, a Python script that brings the classic word-guessing game to life. This implementation challenges players to guess a hidden word one letter at a time, with only a limited number of attempts (lives) before facing the consequences. The game is designed for Python 3 and provides a fun way to test your vocabulary and deductive skills.

## Getting Started

To play the Hangman Game, follow these simple steps:

1. **Prerequisites**: Ensure you have Python 3 installed on your computer.

2. **Download**: Download the `hangman.py` script to your local machine.

3. **Running the Game**:
   - Open a terminal or command prompt.
   - Navigate to the directory where `hangman.py` is located.
   - Run the script with the following command:

     ```
     python hangman.py
     ```

## Gameplay Rules

Here's how the game works:

- When you start a new game, you'll see a word teaser, with each letter of the target word represented by an underscore.

- You begin with 7 lives, and your goal is to guess the word correctly before running out of lives.

- Input one letter at a time when prompted.

- If your guess is correct, the corresponding letter will be revealed in the word teaser.

- An incorrect guess results in the loss of a life, and you'll be informed of the remaining lives.

- The game continues until you successfully guess the entire word or exhaust your lives.

- To exit the game at any point, simply type 'exit'.

## Example Gameplay

Here's an example of the Hangman Game in action:

```
New game started... your word is 7 characters long
To exit the game at any point, type 'exit'
_ _ _ _ _ _ _ 
Clue: A game played by gentlemen
Enter a letter: c
You are correct!
c _ _ _ _ _ _ 
Enter a letter: r
You are correct!
c r _ _ _ _ _ 
Enter a letter: i
You are correct!
c r i _ _ _ _ 
Enter a letter: o
You are correct!
c r i _ _ _ o 
Enter a letter: k
You are correct!
c r i _ _ _ o k 
Congratulations... you have won this round!
```

## Author

This Hangman Game script is authored by Aditya Vijay. Enjoy the challenge!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for complete details.

Have a great time playing Hangman!
