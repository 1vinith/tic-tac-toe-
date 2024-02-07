# tic-tac-toe-
# Detailed explaination of the code components 
Document Structure:

<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Specifies the language of the document.
Head Section:

Contains metadata and links to external resources like CSS files and JavaScript scripts.
Sets the character encoding and viewport for responsive design.
Title and Styles:

<title>: Sets the title of the HTML document.
<style>: Contains CSS styles for styling various elements of the game.
Body Section:

Contains the visible content of the webpage.
Container and Heading:

<div class="container">: Provides a container for the game elements.
<h1>: Displays the heading "Tic Tac Toe".</h1>
Score Columns:

<div class="scores">: Wraps the score columns.
<div class="score-column" id="player1-score">: Displays the score for Player 1.</div>
<div class="score-column" id="player2-score">: Displays the score for Player 2.</div>
Game Board:

<div class="board" id="board">: Contains the game board grid.
<div class="cell" id="cell-0" onclick="handleClick(0)">: Represents each cell in the game grid. Each cell is clickable and has an ID corresponding to its index.
The handleClick(index) function is called when a cell is clicked. It updates the board state, checks for a winner, and updates the scores accordingly.
JavaScript:


Contains the script to handle game logic.
Manages player turns, checks for a winner or draw, updates scores, and resets the board.
Functions:

handleClick(index): Handles the click event on the game cells.
checkWinner(): Checks if there is a winner after each move.
announceWinner(player): Alerts the winner and updates the scores.
announceDraw(): Alerts when the game ends in a draw.
updateScores(player): Updates the scores for Player 1 or Player 2.
resetBoard(): Resets the game board after each game.
Script Execution:

JavaScript functions are executed as the user interacts with the game.
