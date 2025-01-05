# Pig Game

Pig Game is a fun browser-based game for two players. The goal is to score the maximum points by rolling dice and strategically holding points.

## How to Play

1. The game starts with a score of zero for both players.
2. A player rolls the dice by clicking the "Roll dice" button.
   - If the dice shows a 1, the player's current score is reset, and the turn passes to the next player.
   - If the dice shows any other number, it is added to the player's current score.
3. The player can click the "Hold" button to save their current score into the total score and pass the turn.
4. The game continues until one of the players reaches the predetermined winning score (default: 100).


## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/g3nri/pig-game.git
   ```

2. Navigate to the project folder:

   ```bash
   cd pig-game
   ```

3. Open the `index.html` file in your browser.

## Project Structure

- `index.html` - The main HTML file of the application.
- `style.css` - Styles for the user interface.
- `script.js` - Core JavaScript code for the app.
- `dice-1.png` to `dice-6.png` - Dice face images.

## Author

Based on an educational project by [Jonas Schmedtmann](https://twitter.com/jonasschmedtman).

This project was developed to showcase skills in JavaScript, DOM manipulation, and creating dynamic games.
