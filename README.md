# Pool Game
This game is a billiard simulation developed using Python and the libraries Pygame and Pymunk. The main goal of the game is to reach the final (5th) level. In each level, the player must hit specific balls, and hitting the wrong balls reduces the player's lives. The game is designed to be engaging and challenging, with dynamic elements and realistic physics.

## Technologies
Python: Main programming language.

Pygame: Library for creating graphics and handling user input.

Pymunk: Physics engine used to simulate realistic ball movements and collisions.

## Game Features
Realistic Physics: The Pymunk library provides realistic physics, especially noticeable during ball collisions and interactions with the table edges.

Multiple Levels: Each level has a different number of target balls that need to be hit.

Information Display: The game displays the current level, remaining lives, and the number of target balls.

Cue Stick Animation: The cue stick rotates based on mouse movement, showing the direction of the shot.

Dynamic Power Bar: The power of the shot increases and decreases over time while the player holds down the mouse button.

## How to Play
Objective: Hit the target balls in each level to progress to the next level.

Lives: You start with 3 lives per level. Hitting the wrong ball reduces your lives.

Cue Stick: Rotate the cue stick using the mouse to aim.

Shooting: Hold down the mouse button to charge the shot. Release to strike the ball.

Winning: Complete all 5 levels to win the game.

## Challenges Faced
Pymunk Integration: Implementing realistic physics using the Pymunk library was one of the biggest challenges, especially in handling ball collisions and edge bounces.

Level Design: Designing levels with varying numbers of target balls and ensuring balanced difficulty.
