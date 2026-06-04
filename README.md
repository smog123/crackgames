# CrackGames

CrackGames is a simple number guessing game written in Go.

The program generates a random 4-digit secret number, and the player keeps guessing until all digits are correctly matched in their exact positions.

---

## Features

- Generates a random 4-digit number
- Accepts user input from the keyboard
- Checks digits position by position
- Displays correct digit positions
- Continues until the user guesses correctly

---

## Project Structure

```bash
crackgames/
│
├── main.go
└── keyboard/
    └── keyboard.go
