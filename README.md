# NumberGame

# Number Guessing Game

The Number Guessing Game is a simple console-based Java game where the player tries to guess a randomly generated number within a specified range.

## How to Play

1. The game will generate a random number between a predefined minimum and maximum range. By default, the range is set to 1-100.

2. You have a limited number of attempts (default: 10) to guess the correct number.

3. After each guess, you will receive feedback:
   - If your guess is outside the valid range, you'll be prompted to try again.
   - If your guess is too low, you'll receive a "Too low. Try again." message.
   - If your guess is too high, you'll receive a "Too high. Try again." message.
   - If you guess correctly, you'll see a "Congratulations! You guessed the number." message and your score will increase.

4. If you reach the maximum number of attempts without guessing the correct number, the game will display the correct number and inform you that you've reached the maximum attempts.

5. After each round, you have the option to play again. Type "yes" to play another round or anything else to exit the game.

6. The game will keep track of the number of rounds played and your score (number of times you guessed the number correctly).

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your system.
- A Java IDE or text editor to run the game.

### Running the Game

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/RajshriYeske/NumberGame.git
