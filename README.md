Spin and Win Game
This is a simple command-line Spin and Win Game implemented in JavaScript. Players can deposit money, place bets on lines, spin the slot machine, and potentially win prizes based on matching symbols on the lines.
Table of Contents
Installation
Gameplay
Rules
File Structure
Technologies Used
Author
License
Installation
Before running the game, make sure you have Node.js installed on your machine. You also need to install the prompt-sync package. You can install it using npm:
bash
npm install prompt-sync@4.2.0

Gameplay
After installing dependencies, run the game by executing the following command in your terminal:
bash
node project.js

Follow the prompts to play the game:
Deposit some money to start playing.
Choose the number of lines to bet on (1-3).
Enter the bet amount per line.
Spin the slot machine and see the result.
Check if you've won and collect your winnings.
Decide whether to play again.
Rules
The slot machine consists of 3 reels and 3 rows.
Each reel contains symbols (A, B, C, D) with varying frequencies.
Players can bet on 1 to 3 lines.
Winnings are calculated based on matching symbols on the selected lines and their respective bet amounts.
File Structure
project.js: This file contains the JavaScript code for the slot machine game.
package.json: Metadata about the project, including dependencies.
README.md: This file, providing instructions and information about the game.
Technologies Used
JavaScript
Node.js
prompt-sync package for synchronous user input prompts.
Author
Sahasra-Kesara
License
This project is licensed under the ISC License.
