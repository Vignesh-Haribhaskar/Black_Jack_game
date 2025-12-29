# Blackjack Game (Python – OOP)

This is a **command-line Blackjack game** built using **Object-Oriented Programming (OOP)** in Python.  
The project was created as part of my **Python fundamentals and software engineering practice**.

---

## 🎯 Project Overview

The game simulates a classic **Blackjack (21)** card game where:
- A player competes against the dealer
- Cards are shuffled and dealt from a standard deck
- Blackjack rules are enforced
- The game supports multiple rounds

---

## 🧠 Concepts Used

This project focuses on **clean code structure and OOP principles**:

- Classes and objects
- Encapsulation
- Game state management
- Control flow and loops
- Input validation
- Randomization (`random` module)

---

## 🧱 Class Structure

- **Card**
  - Represents a single playing card (suit + rank)

- **Deck**
  - Creates a full 52-card deck
  - Shuffles cards
  - Deals cards to players

- **Hand**
  - Stores cards for player or dealer
  - Calculates hand value
  - Handles Blackjack logic (Aces, busts)

- **Game**
  - Controls the game flow
  - Handles user input
  - Determines winners

---

## ▶️ How to Run

1. Make sure Python is installed (`python 3.x`)
2. Clone the repository or download the file
3. Run the game using:

```bash
python blackjack.py
