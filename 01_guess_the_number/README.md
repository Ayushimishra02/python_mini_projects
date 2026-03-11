# 🎯 Guess The Number Game (Python)

## 📌 Project Overview

This project is a **command-line based guessing game built in Python**.
The program randomly generates a number between **1 and 100**, and the user attempts to guess it. Based on the user's guess, the system provides hints indicating whether the guess is **close ("Hot")** or **far ("Cold")** from the target number.

The project was created to practice **core Python programming concepts and logical problem solving**.

---

## 🎮 How the Game Works

1. The program generates a random number between **1 and 100**.
2. The user inputs a guess.
3. The program evaluates the guess:

   * **🔥 Hot** → Guess is within ±10 of the target number.
   * **❄️ Cold** → Guess is far from the number.
   * **✅ Right** → Correct guess.
4. The game continues until the correct number is guessed.

---

## 🧠 Programming Concepts Demonstrated

This project demonstrates practical use of several Python fundamentals:

* **Functions** for modular code design
* **Loops** (`while`) for repeated execution
* **Conditional logic** (`if / elif / else`)
* **Random number generation** using Python's `random` module
* **User input handling**
* **Basic game logic implementation**

---

## 🏗️ Code Design

The project follows a **modular structure**, separating responsibilities into functions:

| Function                  | Purpose                                              |
| ------------------------- | ---------------------------------------------------- |
| `getRandomNumber()`       | Generates a random number between 1 and 100          |
| `giveHint(number, guess)` | Evaluates the guess and returns the appropriate hint |
| `runGuess()`              | Runs the main game loop and handles user interaction |

This separation makes the code **easier to maintain and extend**.

---

## 📂 Project Structure

```
01_guess_the_number
│
├── main.py
└── README.md
```

---

## ▶️ Running the Program

### 1️⃣ Clone the repository

```
git clone https://github.com/Ayushimishra02/python_mini_projects.git
```

### 2️⃣ Navigate to the project folder

```
cd python_mini_projects/01_guess_the_number
```

### 3️⃣ Run the program

```
python main.py
```

---

## 💡 Example Interaction

```
Enter a number between 1 and 100: 20
Cold
guess again

Enter a number between 1 and 100: 52
Hot
guess again

Enter a number between 1 and 100: 56
You guessed it Right!
```

---

## 🚀 Future Improvements

Possible extensions that can make the project more robust:

* Limit number of attempts
* Track number of guesses
* Add difficulty levels
* Implement score system
* Create a graphical interface version
* Convert into a web-based mini game

---

## 📚 Learning Outcome

While building this project I practiced:

* Breaking a problem into smaller functions
* Writing reusable code
* Handling user input safely
* Implementing simple decision-based algorithms

---

## 👩‍💻 Author

**Ayushi Mishra**
Computer Science Student

Currently exploring:

* Python development
* Data structures and algorithms
* Machine learning and applied AI projects

This repository documents my **progressive learning through small hands-on programming projects.**
