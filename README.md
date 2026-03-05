Brick Breaker Game
Description

The Brick Breaker Game is a grid-based simulation where a ball is launched to break bricks placed inside a bounded area. Each brick has a strength value, representing the number of hits required to destroy it. The ball moves in different directions and interacts with walls and bricks based on defined mechanics.

The objective is to destroy all bricks using limited ball lives.

Grid Structure

The game uses a 7 × 7 grid with the following elements:

Symbol	Meaning
w	Wall (boundary of the game area)
g	Ground
o	Ball position
1,2,3...	Bricks with strength values
Initial Setup

Grid Size: 7 × 7

Number of Bricks: 6

Brick Positions:
(2,2), (2,3), (2,4), (3,2), (3,3), (3,4)

Initial Ball Lives: 5

Ball Movement Commands
Command	Description
St	Ball moves straight upward
Lt	Ball moves diagonally left upward
Rt	Ball moves diagonally right upward
Game Mechanics

When the ball hits a brick, its strength decreases by 1.

If the brick's strength becomes 0, the brick disappears.

The ball then moves into that brick's position.

If the ball hits a wall, it reflects based on the direction of impact.

After each move, ball count decreases by 1.

Objective

Destroy all bricks before the ball lives run out.

Project Modules

The game is designed in 7 progressive modules, each introducing additional mechanics and complexity.

<img width="478" height="263" alt="Screenshot 2026-03-05 210504" src="https://github.com/user-attachments/assets/8b0004d0-9644-4e09-a1ce-93e6452cf0c0" />
