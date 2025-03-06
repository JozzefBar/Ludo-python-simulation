
# Ludo Game Simulation 

This project is an implementation of the **Ludo game**, developed in **Python** as part of the **Programming 1** course at **FEI STU**. The goal of this project was to apply and evaluate the programming skills we acquired during the course.

## Important Note
This project is a **simulation** of the Ludo game. The entire code, including variables, comments, outputs and the project description at the beginning of the code, is written in **Slovak!!!**. 
Added PDF, where the description of the entire project, including its evaluation, is also in **Slovak!!!**.

## Modified Rules

- 👨‍🦰 **Number of Players**: The number of players is **fixed at 2** *(Player A/Player B)* and cannot be changed.
- ♟️**Single Piece Simulation**: At the start of the game, each player has only **one piece** on the board. Once the piece reaches the home area, a new piece is moved to a starting position. The game continues with one piece at a time per player.
- 🏁 **Board Size**: The player can specify any **odd-numbered board size** greater than **3**. This allows for more home areas (more than the usual 4) to be included. 
- 🎲 **Dice Rolls**: Dice rolls follow normal **Ludo game rules**. If a player rolls a **6**, they get another turn. Players must roll the exact number needed to land in the home area. If more than one home area is filled, the player continues to roll the dice until they get the required number. If there are more than 6 home areas (more than the maximum roll of the dice), the piece only needs to reach the first home area after rolling a dice and will be automatically added to the closest free home area.
- 🚶‍♂️ **Player Elimination**: If a player’s piece lands on an opponent’s piece, the opponent's piece is moved back to the starting position next round. 

*(Detailed game rules can be found in the provided PDF.)*
## How to Play

1.  Enter the **board size** (The number must be odd and greater than 3.).
2.  The game will begin, and players will take turns rolling the dice and moving their pieces according to the rules.
3. The first player to move all of their pieces to the home area wins the game. After the simulation is complete, the winner will be **announced**.

## **Game Output Details**

The following are the key outputs displayed during the game simulation:

1.  **Round Information** – Each round, the current turn and player are displayed, along with the result of the dice roll.
2.  **Player Move** – When a player moves their piece, the output will show the updated position of the piece on the board.
3.  **Piece Moving to Home Area** – When a player’s piece reaches the home area, a message will indicate that the piece has successfully entered the home.
4.  **Winner Announcement** – When a player moves all their pieces to the home area, the program announces the winner of the game.
5. **Game Board Display** – The entire game board is shown with the pieces and home areas, illustrating the current state of the game.
6. **There is no written output when piece is taken by another player!**

*Below are example screenshots from the simulation, illustrating the various outputs.*
*******todo
## Setup
To run the game, make sure you have **Python 3.x** installed on your system. It's recommended to use **Visual Studio** or another IDE for best results, as the script close immediately when run in a command prompt.

## Project Evaluation

The project was evaluated based on the criteria specified in the provided **PDF** document, which includes coding standards, functionality, and the implementation of game rules. 



