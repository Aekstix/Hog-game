# Hog-game

A single or 2 player dice game


# Objective: 
Be the first player to reach the target score
Players switch turns and choose how many dice to roll
If any rolled dice gives 1 the players only earns 1 point that turn
. Rules: Boar brawl- if you choose to roll 0 dice then you earn points based on the tens digit of your opponent's score and the ones digit of your own score. The points you earn is based on the formula max(1,abs(2(opponents tens digit - your ones digit))) this formula chooses 1 if the amount of points you score by rolling zero dice is less than 1. 
Sus Fuss - Sus fuss is a special rule that checks your score after your turn. If you score is a prime number then it stays the same, but if your score is not a prime number then it increases to the next prime number.


# How to play 
Windows: Open command prompt and navigate to the hog folder where you extracted the game and run the following commands based on how you want to play.
Mac: Open terminal and go to the hog folder where you extracted the game and run the following commands based on how you want to play.
Linux: Open terminal and go to the hog folder where you extracted the game and run the following commands based on how you want to play.

# Commands
If you want to watch 2 computers play run python3 hog_ui.py for mac and linux. Run py hog_ui.py for windows
if you want to play against a computer run python3 hog_ui.py -n 1 for mac and linux. Run py hog_ui.py -n 1 for windows
if you want to play against a friend or someone else run python3 hog_ui.py -n 2 for mac and linux. Run py hog_ui.py -n 2 for windows
Finally if you want to play the graphic interface run python3 hog_gui.py for mac and linux. Run py hog_gui.py
