# Number-Game


The Number Game is a simple Java-based console game where players try to guess a randomly generated number within a limited number of attempts. It's a fun and interactive game that tests the player's intuition and number-guessing skills.

Game Rules
The game generates a random number between 1 and 100 at the start of each round.
Players have 8 chances to guess the correct number.
After each guess, the game provides feedback:
Too High: The guessed number is higher than the target number.
Too Low: The guessed number is lower than the target number.
Correct Guess: The player guessed the correct number and wins the round.
If the player fails to guess the number within the allowed attempts, the correct answer is revealed, and they lose the round.
After each round, players can choose to play again by entering "y" for yes or "n" for no.
Features
Random Number Generation: The game generates a new random number between 1 and 100 at the start of each round.
Score Tracking: The game keeps track of the number of rounds won by the player.
Play Again Option: Players can choose to play multiple rounds in a single session.
How to Run the Game
Clone or download this repository.
Open the project in a Java IDE or compile it using the terminal.
Run the NumberGame class to start the game.
Example Gameplay

Let's Play!
Hi Friends, you have about 8 chances to win the game.
chance 1: Enter your guess:
> 50
Too High
chance 2: Enter your guess:
> 25
Too Low
chance 3: Enter your guess:
> 35
You win it!
Do you want to play again? (y/n)
Technologies Used
Java: Core programming language for the game.
Java Scanner: Used for reading user input from the console.
Math.random(): Generates random numbers for the game.
