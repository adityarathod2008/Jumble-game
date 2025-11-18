🧩 Jumble Game (Python)

A fun and interactive Jumble Word Game built using Python.
The game picks 10 random words, jumbles their letters, and challenges the player to guess them. With scoring, rules, and a basic login system, this project is great for beginners exploring Python programming.

🚀 Features

🎮 10-round word jumble quiz

🔀 Words are selected randomly from a large word list

🧠 Each correct guess awards +10 points

❌ Each wrong answer deducts –2 points

🔐 Simple login system (username + password)

👤 Personalized greeting using player's name

📘 Beginner-friendly and easy to modify

📂 How the Game Works

User logs in (default username: aditya's game, password: password)

Player enters their name.

Game shows rules and begins.

In each round:

A random word is selected.

Letters are shuffled.

Player guesses the original word.

Total score is shown at the end.

🛠️ Technologies Used

Python 3

random module for shuffling and word selection

Basic input/output and conditions

📜 Rules of the Game

Total 10 questions

+10 points for each correct answer

–2 points for each wrong answer

Enter the word exactly as spelled (first letter capital)

▶️ How to Run
python jumble_game.py

📦 Code Overview

game() → Handles the quiz, scoring, and shuffled words

login() → Simple hard-coded login system

List of 150+ random English words included

🧩 Sample Output
Enter your name: Aditya
Welcome Aditya
Welcome to jumble game:
Jumbled word: ['P','y','t','h','o','n']
Enter Your Answer: Python
Good! Your answer is right.

📝 Future Improvements

Add difficulty levels

Add hints

Improve login system

Store scores in a file

Add GUI using Tkinter or PyGame

📄 License

This project is open-source under the MIT License.
