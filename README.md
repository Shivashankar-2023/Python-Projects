PYTHON PROJECTS

1) PROJECT 1 - 🐍 Snake Water Gun - Python Game

A simple command-line game in Python where you play **Snake 🐍, Water 💧, or Gun 🔫** against the computer.  
This is similar to Rock Paper Scissors, but with a twist in rules!

- Snake drinks Water → Snake wins 🐍 > 💧
- Water damages Gun → Water wins 💧 > 🔫
- Gun kills Snake → Gun wins 🔫 > 🐍
- Same choice → It's a Tie!

## 🧠 How It Works

- The computer randomly selects one option: Snake (`s`), Water (`w`), or Gun (`g`)
- You are prompted to input your choice
- The game then compares both choices and announces the winner



2) PROJECT 2 -🎯 Number Guesser Pro

A simple and fun Python terminal game where you try to guess a number between 1 and 100.  
Tracks and stores your best (lowest) number of guesses in a `hiscore.txt` file.

## 📌 Features

- Random number between 1 and 100
- Counts how many guesses you take
- Compares your score with a saved high score
- Stores the best score in `hiscore.txt`
- Friendly feedback for higher/lower guesses

## 🧠 How It Works

1. The computer randomly picks a number from 1 to 100
2. You keep guessing until you get it right
3. It tells you whether to go higher or lower
4. When you guess correctly:
   - It tells you how many guesses you took
   - If your guesses are fewer than the saved high score, it updates the score in `hiscore.txt`

### Prerequisites
- Python 3.x installed

### Running the Game

1. Save your code in a file (e.g., `number_guesser.py`)
2. Create an empty text file named `hiscore.txt` with a starting value (like `999`)
3. Run the game





3) PROJECT 3 - 📚 Central Library Console App

A simple command-line Library Management System in Python that allows users to:
- View available books
- Borrow a book
- Return a book

Built using Object-Oriented Programming (OOP) concepts with `Library` and `Student` classes.

## 🧠 How It Works

- The **Library** class handles:
  - Displaying books
  - Issuing (borrowing) books
  - Accepting returned books
- The **Student** class handles:
  - Requesting a book
  - Returning a book
A menu-driven interface allows the user to perform operations through the console.

## 📌 Features

- View a list of available books
- Borrow a book (if available)
- Return a book
- Console-based interaction using a menu
- OOP-based clean class structure
