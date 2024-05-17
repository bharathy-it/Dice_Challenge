## Project Description
Welcome to the Dice Challenge! This simple yet entertaining web application simulates a dice roll challenge between two players. 
The project showcases basic JavaScript functionality to generate random numbers and dynamically update the webpage content based on these values.

## Features
Random Dice Roll: On every page refresh, two dice are rolled randomly to display a number between 0 and 6.
Player 1 vs Player 2: Two dice images are displayed for Player 1 and Player 2.
Winner Announcement: The webpage declares the winner based on the higher dice roll:

If Player 1's dice shows a higher number, it displays "Player 1 wins".
If Player 2's dice shows a higher number, it displays "Player 2 wins".
If both dice show the same number, it displays "Draw".

## How It Works
Dice Images: There are 7 images representing dice faces from 0 to 6.

## JavaScript Logic:
Math.random() is used to generate random numbers between 0 and 6 for both dice.
querySelectorAll() selects the dice image elements in the DOM.
The dice images are updated based on the generated random numbers.
A simple comparison determines the winner or if it's a draw.

## Technologies Used
HTML: For structuring the webpage.
CSS: For basic styling.
JavaScript: For the game logic, random number generation, and DOM manipulation.
