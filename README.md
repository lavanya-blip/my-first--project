# my-first-project
This is my first GitHub project created for practising coding and learning Git.


🎯 Number Guessing Game

A simple and fun command-line number guessing game written in Python.
The program randomly selects a number between 1 and 500, and the player must guess the number.
After each guess, the game provides hints until the correct number is found.



📌 Features

Randomly generates a secret number between 1 and 500

Tracks the number of attempts made by the player

Provides helpful hints:

“Too low!” if the guess is smaller than the secret number

“Too high!” if the guess is larger than the secret number

Handles invalid inputs gracefully

Simple and beginner-friendly Python example.


🧠 How It Works

The game starts and selects a secret number using:

secret_number = random.randint(1, 500)


The player enters guesses in a loop.

Each guess is compared with the secret number.

The loop continues until the correct number is guessed.

The game displays the total number of attempts.

▶️ How to Run

Make sure you have Python 3 installed.

Save the script as guess_the_number.py

Open a terminal or command prompt

Run:

python guess_the_number.py



📥 Sample Output
Welcome to the Number Guessing Game!
I have picked a number between 1 and 500. Try to guess it.
Enter your guess: 200
Too low! Try again.
Enter your guess: 350
Too high! Try again.
Enter your guess: 300
🎉 Congratulations! You guessed the number 300 in 3 attempts.
