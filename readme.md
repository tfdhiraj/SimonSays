Simon Game

A simple Simon game implemented using HTML, CSS, and JavaScript. Simon is a memory game where the player needs to repeat a sequence of flashing blocks. The game consists of different levels, and the goal is to reach higher levels by successfully repeating the sequences.

Features

Play Button: Clicking the "Play" button initiates a sequence of flashing blocks.
Game Blocks: The player needs to click on the blocks in the same order as they flash.
Levels: Successfully completing a level increases the player's score and advances to the next level.
Restart Button: Allows the player to restart the game at level 1.
Leaderboard: Displays the player's scores for each session.

Usage

Open the HTML file in a web browser.
Click the "Play" button to start the game.
Repeat the sequence of flashing blocks by clicking on them.
Successfully completing a level increases the score and advances to the next level.
If the player makes a mistake, the game resets, and the score is added to the leaderboard.


Code Overview

HTML Elements
play: Button to start the game.
restart: Button to restart the game.
blocks: Game blocks that flash in a sequence.
levelno: Element to display the current level.
result: Element to display game results.
leaderboard: Container for displaying past scores.
JavaScript Variables
order: Array to store the sequence of flashing blocks.
canPlayerPlay: Flag to control player interaction.
level: Current game level.
score: Player's current score.
pastScores: Array to store past scores.


Functions
flash(block): Asynchronous function to make a block flash. Returns a promise.
Event Listeners on Blocks: Handle player clicks on game blocks, check if the correct block is clicked, update the score, and display game results.
play Event Listener: Initiates the game by generating a sequence of flashing blocks asynchronously.
restart Event Listener: Resets the game to level 1.
Local Storage
The game stores past scores in the local storage to persist across sessions.
Credits
This game was created by [Your Name] (replace with your name or username).


Feel free to use, modify, and distribute the code as needed.