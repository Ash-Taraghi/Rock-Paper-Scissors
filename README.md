# Rock, Paper, Scissors Game

This is a simple Rock, Paper, Scissors game that you can play against the computer. The game is built using HTML, CSS, and JavaScript.

## How to Play

1. Open the `index.html` file in your web browser.
2. You will see the game interface with rules and options to choose from (Rock, Paper, Scissors).
3. Click on your choice (Rock, Paper, or Scissors).
4. The computer will randomly select its choice.
5. The result of the round will be displayed, and the scores will be updated.
6. The first one to three points wins the game.
7. Once the game is over, you can click the "Play again?" button to reset the game and play again.

## File Structure

- `index.html`: The main HTML file that contains the structure of the game.
- `styles.css`: The CSS file that styles the game.
- `script.js`: The JavaScript file that contains the game logic.

## HTML Structure

- `index.html`: Contains the main layout of the game, including the rules, score display, option buttons, and results messages.

## CSS Styling

- `styles.css`: Styles the game interface, including the layout, colors, and button styles. The color theme includes:
  - Background color: Dark Blue
  - Text color: Light Blue
  - Button color: Orange with a light orange gradient
  - Rules container: Light Blue with a dark blue border

## JavaScript Logic

- `script.js`: Contains the game logic, including:
  - Randomly selecting the computer's choice.
  - Determining the winner of each round.
  - Updating the scores.
  - Displaying the results and winner messages.
  - Resetting the game.

## Functions

### `getRandomComputerResult()`

Returns a random choice (Rock, Paper, or Scissors) for the computer.

### `hasPlayerWonTheRound(player, computer)`

Determines if the player has won the round based on their choice and the computer's choice.

### `getRoundResults(userOption)`

Handles the game logic for a single round, updates the scores, and returns the result message.

### `showResults(userOption)`

Displays the results of the round and updates the scores and messages on the screen.

### `resetGame()`

Resets the game state, including the scores and messages, and makes the game ready for a new round.

## Event Listeners

- Adds click event listeners to the Rock, Paper, and Scissors buttons to trigger the game logic.
- Adds a click event listener to the "Play again?" button to reset the game.

## How to Run

1. Clone the repository or download the files.
2. Open the `index.html` file in your web browser.
3. Start playing the game by clicking on your choice (Rock, Paper, or Scissors).

Enjoy playing Rock, Paper, Scissors!