Jumble Game

A simple and fun Jumble Game implemented in Python. Test your vocabulary and spelling skills by guessing the correct word from a jumbled set of letters!

Features

Login system to start the game.

10 questions per game session.

Each correct answer gives 10 points.

Each wrong answer deducts 2 points.

Random words from a pre-defined list.

Interactive console-based gameplay.

Rules

There will be a total of 10 questions.

For each correct answer, you earn 10 points.

For each wrong answer, 2 points are deducted.

When entering your answer, type it with only the first letter capitalized (e.g., Python).

How to Play

Run the Python script:

python jumble_game.py


You will be prompted to login:

Enter valid user name : 
Enter password :


Username: aditya's game

Password: password

After logging in, you will see a jumbled word.

Type your guess and press Enter.

Your score will be displayed at the end of the game.

Example Gameplay
Enter your name: Aditya
Welcome Aditya
Welcome to jumble game:
Here are some rules of game
1. There will be total 10 question
2. For each right answer you get 10 points
3. For each wrong answer your point will be min. by 2 points
4. When you enter your ans. enter only first word capital

['p', 'y', 't', 'h', 'o', 'n']
Enter Your Answer: Python
Good! Your answer is right.
...
Your total score is 78

Requirements

Python 3.x

No external libraries required (uses only the built-in random module)

How It Works

The program randomly selects a word from a predefined list.

It jumbles the letters of the word.

The player guesses the original word.

Score is calculated based on correct/incorrect answers.
