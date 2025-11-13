# My_First_Python_Project_
# Memory Match Game

**Flip cards and match pairs**

**Python Capstone Project — FY AIML, Sanjivani University**

---

## Project Overview
A simple, beginner-friendly memory match (concentration) game implemented in Python using the Tkinter GUI toolkit. The game places 8 pairs of emoji cards on a 4×4 grid. The player flips two cards at a time to find matching pairs. The objective is to match all pairs with as few moves as possible.

---

## Group
- Samarth Sadaphal — 2125UMLM1021
- Piyush Gaikwad — 2125UMLM1025
- Yogesh Nawale — 2125UMLM1023
- Preeti Gaikwad — 2125UMLF1024
- Vedika Pangavhane — 2125UMLF1022

**Department:** FY AIML, Sanjivani University

---

## Technologies Used
- **Language:** Python 3.x
- **Library:** Tkinter (built-in Python GUI toolkit)

---

## Features
- 4×4 grid of cards (16 cards — 8 emoji pairs)
- Randomized card placement each game
- Visual feedback when two cards match (highlighted)
- Brief delay after the second card flip so the player can see cards
- Progress/status label and completion message
- Restart button to reshuffle cards and reset the game

---

## How the Game Works (Logic)
1. Create a list of 8 distinct symbols (emoji). Duplicate and shuffle them to form 16 cards.
2. Create 16 Tkinter `Button` widgets arranged in a 4×4 grid.
3. When a player clicks a button, reveal the emoji and disable the button temporarily.
4. After two cards are revealed, wait (e.g. 500 ms) and check for a match:
   - If they match: keep them revealed and visually mark them as matched.
   - If not: flip them back (hide) and re-enable.
5. Track matched pairs; when it reaches 8, show a completion message.
6. Restart reshuffles the cards and resets UI.

---

## Installation / Requirements
1. Python 3.8+ installed.
2. Tkinter available. Check with:
   ```
   python -m tkinter
   ```

---

## Running the Game
1. Save the script (e.g., `memory_match.py`).
2. Run:
   ```
   python memory_match.py
   ```

---

## Example (pseudocode)
```python
symbols = ['🍎','🍌','🍇','🍓','🍒','🍉','🥝','🍋']
cards = symbols * 2
random.shuffle(cards)
```

---

## Project Demonstrates
- Event-driven programming
- GUI layout with Tkinter
- Randomization
- Basic game logic and state management

---

## Future Improvements
- Timer and move counter
- Difficulty levels
- Sound effects and animations
- Save high scores
- Responsive UI design

---

## Acknowledgments
Thanks to Rajeshwar Gupta Sir and the FY AIML department for guidance.

---

## License
Educational use only. Free to modify.

