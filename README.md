# Hog Dice Game

## Objective
Be the first player to reach the target score.

## How to Play
Players take turns and choose how many dice to roll. If any rolled die shows a 1, the player earns only 1 point for that turn. Otherwise, the player earns the sum of the dice rolled.

## Special Rules

**Boar Brawl:** If you choose to roll 0 dice, you earn points based on the tens digit of your opponent's score and the ones digit of your own score. The points earned are calculated using the formula:

`max(1, abs(2 * (opponent's tens digit - your ones digit)))`

This formula ensures that you earn at least 1 point when rolling zero dice.

**Sus Fuss:** Sus Fuss checks your score after your turn. If your score is a prime number, it stays the same. If your score is not prime, it increases to the next prime number.

## How to Run the Game

First, download and extract this repository. Then, open the appropriate terminal or command prompt and navigate to the folder where you extracted the Hog game.

- **Windows:** Open Command Prompt.
- **macOS:** Open Terminal.
- **Linux:** Open Terminal.

Once you are inside the Hog project folder, run one of the commands below depending on how you want to play.

## Commands

### Watch Two Computers Play

- Windows: `py hog_ui.py`
- macOS/Linux: `python3 hog_ui.py`

### Play Against a Computer

- Windows: `py hog_ui.py -n 1`
- macOS/Linux: `python3 hog_ui.py -n 1`

### Play Against a Friend

- Windows: `py hog_ui.py -n 2`
- macOS/Linux: `python3 hog_ui.py -n 2`

### Play Using the Graphical Interface

- Windows: `py hog_gui.py`
- macOS/Linux: `python3 hog_gui.py`

## Requirements

- Python 3 installed on your computer.
