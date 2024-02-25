Gem Hunters console game Youtube Video Link of Screencast video: https://youtu.be/o6yFGvtsttc
The "Gem Hunters" game is a console-based 2D adventure with a 6x6 square board as the battleground. 
Players, denoted as "P1" and "P2," begin their gem-collecting trip from opposite directions. 
The board is studded with expensive gems ("G") strategically placed at the beginning of the game and serves as the coveted prizes. 
Obstacles ("O") create a sense of challenge by impeding player movement.

The game is divided into four fundamental classes: Position, Player, Cell, and Board. The Position class defines coordinates on the board, which helps determine acceptable moves and player locations.
The player incorporates player attributes, including name, current position, and gem count. The Cell class represents individual squares on the board. It includes occupant information, whereas the Board class administers the entire game board, manages display operations, authenticates player moves, and maintains gem collections.

The Game class is the game's central orchestrator, connecting players, the board, and game logic. 
Players take turns navigating the board by typing motions (U, D, L, R) into the console, with each successful move potentially resulting in gem acquisition. 
The game consists of 30 moves (15 turns per participant), with the victor determined by gem count. 
The Start() method initiates the game and displays the initial board state, whereas SwitchTurn() alternates player turns. 
The conclusion is reached using IsGameOver(), and the AnnounceWinner() method exposes the player with the highest gem count or declares a tie if both players have the same score. 

This hierarchical design offers a dynamic and exciting gameplay experience, mixing strategic movement with gem collection to achieve victory within the permitted turns—requirements: .NET Core SDK.

