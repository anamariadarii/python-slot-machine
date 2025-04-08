# 🎰 Python Slot Machine Game

This is a **console-based slot machine simulator**, built entirely in Python, as part of my portfolio to demonstrate:

- Core Python programming skills
- Functional programming style
- Input validation and user interaction
- Use of data structures (`dict`, `list`)
- Random generation logic
- Modular, readable code

---

## 💡 Why I Built This

I wanted to simulate a real-world logic flow using core Python — from **user input** to **random outcome processing**, with **decision logic** and **feedback display**.  
The slot machine mechanic was a fun and practical way to demonstrate:

- Data flow management
- Loop and control structures
- Clean console UX
- Simple algorithm to check winning lines

---

## ⚙️ Technologies Used

| Technology | Description |
|------------|-------------|
| **Python 3** | Entire project is written in standard Python |
| `random` module | For simulating randomized slot machine spins |
| `dict`, `list`, `looping` | Core Python data structures |
| Functional decomposition | Code split into clear, reusable functions |
| CLI interaction | Full user interaction through terminal |

---

## 🔍 What the Code Does

- Accepts **deposit amount** from the user
- Allows betting on **1 to 3 lines**
- Validates inputs for bets and lines
- Randomly spins a **3x3 slot machine grid**
- Calculates **winnings** based on matching symbols
- Displays detailed results to the user after each spin

---

## 🧠 Key Functions

| Function | Purpose |
|---------|---------|
| `deposit()` | Handles money input and validation |
| `get_slot_machine_spin()` | Randomly generates the 3x3 grid |
| `check_winnings()` | Compares symbols per line, returns winnings |
| `spin()` | Full round: betting, spinning, evaluating |
| `main()` | Game loop – keeps running until user quits |

---

## 💬 Example Output

```text
Enter the number of lines to bet on (1-3)? 3
What would you like to bet on each line? $10
You are betting $10 on 3 lines. Total bet is equal to: $30
A | B | A
A | A | A
C | D | B
You won 50
You won on lines: 2
