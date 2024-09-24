# Hangman Game

This is a simple **Hangman** game implemented in C++. The game allows the user to choose a category and then tries to guess a word by entering one letter at a time. The player has a limited number of tries to guess the word before they lose.

## Features
- Multiple categories to choose from:
  - Countries
  - Mobile Phones
  - Harry Potter Characters
  - Programming Languages
  - Famous Scientists
- **Dynamic word generation** based on the selected category.
- **Tracking of guessed letters** to avoid repeated guesses.
- **Feedback** for correct or incorrect guesses.
- **Limited tries** to guess the word (5 maximum attempts).

## How to Play
1. When you start the game, you will be prompted to choose a category.
2. The game will select a random word from the chosen category.
3. Each letter in the word is represented by an asterisk (`*`).
4. You must guess the word by entering one letter at a time.
5. For each incorrect guess, the number of tries decreases. If you run out of tries, the game is over.
6. If you guess the word correctly before running out of tries, you win!

## Categories
1. **Countries**: Popular countries around the world.
2. **Mobile Phones**: Common mobile phone brands.
3. **Harry Potter Characters**: Characters from the Harry Potter universe.
4. **Programming Languages**: Popular programming languages.
5. **Famous Scientists**: Notable scientists from history.

## Sample Gameplay

Choose a category:
1. Countries
2. Mobile Phones
3. Harry Potter Characters
4. Programming Languages
5. Famous Scientists

Enter your choice (1-5): 3

Guess a letter: h

You found a letter! Isn't that exciting!

Guess a letter: z

Whoops! That letter isn't in there!

You have 4 guesses left.
```

## Dependencies
- Standard C++ libraries (`<iostream>`, `<vector>`, `<random>`, `<string>`, `<set>`, `<algorithm>`, `<cctype>`, `<limits>`)

## How to Compile and Run
1. Compile the code using a C++ compiler (e.g., `g++`):
    g++ hangman.cpp -o hangman
2. Run the game:
    ./hangman

## Future Enhancements
- Add more categories.
- Include hints for each word.
- Add a graphical representation of the hanging process.


