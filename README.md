# crafting-the-way

## Introduction

This project is a board game inspired by the rules of a popular board game.  
The game was developed by adopting MVC architecture and applying OOP.

## Game Rules

- Players can place walls at any location they want, **with one exception**:  
Walls should not completely block any piece, including their own.
- Players can move one square up, down, left, or right in one turn.  
  Diagonal movement is not available unless each player's pieces face each other.

## Implementation

- BGLogic checks if the player's piece can move and whether the wall can be placed.
- The validity of the wall placement requested by the player is checked by DFS.
- Only when the player's request is valid will the changes be reflected through BGFrame.

## Demo

The demo video is played at 1.5x speed.

## Additional Info
- In order to distribute the project publicly, I recently renamed some files and variables in the source code.  
  **but there were no changes to the logic.**  
- I got consent to distribute the source code to the team members who worked on the project together.  
- It works well in most cases, but there are bugs in some edge cases.  
  I would appreciate it if you could contribute to fixing this!  
