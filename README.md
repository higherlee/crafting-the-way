# crafting-the-way

## Introduction

This project is a board game inspired by the rules of a popular board game.  
The game was designed with an MVC architecture.

## Game Rules

<img width="1100" alt="game_rules" src="https://github.com/user-attachments/assets/21785a1f-e490-4075-9170-c9c36e4956ec" />

- Players can place walls at any location they want, **with one exception**:  
Walls should not completely block any piece, including their own.
- Players can move one square up, down, left, or right in one turn.  
  Diagonal movement is not available unless each player's pieces face each other.

## Implementation

<img width="1100" alt="class_diagram" src="https://github.com/user-attachments/assets/abf5a0ab-b4d0-4c3d-bfe8-3e6ed331667f" />

- BGLogic checks if the player's piece can move and whether the wall can be placed.
- The validity of the wall placement requested by the player is checked by DFS.
- Only when the player's request is valid will the changes be reflected through BGFrame.

## Demo

https://github.com/user-attachments/assets/47285008-d20d-426f-8caa-26826c9dc8e4

The demo video is played at 1.5x speed.

## Additional Info
- **This project was completed in 2022.** I got consent to distribute the source code to the team members who worked on the project together.  
- In order to distribute the project publicly, I recently renamed some files and variables in the source code. **but there were no changes to the logic.**  
- It works well in most cases, but there are bugs in some edge cases.  
  I would appreciate it if you could [contribute](https://github.com/higherlee/crafting-the-way/pulls) to fixing this! 
