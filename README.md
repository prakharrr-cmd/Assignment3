THIS IS A README FILE FOR MY SNAKE GAME(ASSIGNMENT 3).
1. Game Idea

The Snake Game is a classic retro-style console game where the player controls a moving snake inside a rectangular boundary.
The snake continuously moves in a direction, and the player’s goal is to eat fruits, which makes the snake grow longer.
The game ends when the snake collides with the walls or its own tail.

This project demonstrates the use of:

Loops

Functions

Arrays

Conditional statements

Keyboard input handling

Random number generation

Console-based graphics

It is designed as a simple but complete game for beginners learning C programming.

🟨 2. Rules of the Game

The snake moves continuously inside the 40×20 grid.

A fruit appears at a random location inside the grid.

When the snake eats the fruit:

Score increases by 10 points

Snake tail increases in length

The game ends if:

The snake hits a wall

The snake bites its own tail

Player can exit the game at any time by pressing X.

🟦 3. Controls
Key	Action
W	Move Up
A	Move Left
S	Move Down
D	Move Right
X	Quit Game

These controls ensure smooth and intuitive movement for the player.

🟪 4. Features

✔ Console-Based Graphics

Boundaries are drawn using #

Snake head (O), body (o), and fruit (F) are clearly visible

✔ Random Fruit Placement

Fruit appears at a new random location each time it is eaten

✔ Score Tracking

Score increases by 10 with every fruit eaten

Final score is displayed at Game Over

✔ Growing Snake Tail

Snake increases in length as the player eats fruit

✔ Collision Detection

Game checks for wall and self-collision

✔ Replay-Friendly

Clean interface

Fast and smooth movement using Sleep() and kbhit()

🟧 5. Conclusion

The Snake Game demonstrates a complete understanding of C programming basics.
It showcases logic building, game loops, arrays, conditions, and user interaction, making it a perfect project for first-semester students.
