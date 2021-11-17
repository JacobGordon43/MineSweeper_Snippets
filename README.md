# MineSweeper_Snippets
 
## Disclaimer
Due to GCU policy, I can not create public GIT repositories for milestones/assignents. If you would like to see the full code, please contact me at jacobg43@cox.net. The content below is from the readme.md from the Uno Game repository, which explains the milestone more in depth. The contents of this repository hold code snippets of a MineSweeper milestone done in C#. The contents of this repository holds snippets of code/functionality and snippets of the application running, separated between two folders. Below will be an in depth explaination of functionality. 

## Summary
This milestone oversaw the creation of a Minesweeper game in C# using Windows forms. The application contains a project solution for unit testing (which took place for determining if the live neighbor count was calculating correctly), a library solution which contained the board and cell classes, and then a windows form solution which was responsible for implementing game logic with the GUI.

## Funcitonality
There are a number of different functionalities that had to be implemented to create a minesweeper game
- A player has to choose the difficulty in which to operate under
- Generate an interactable board in the GUI
- Create and randomly place mines throughout the board
- Calculate live neighbors for each cell
- Floodfill when a cell with no live cells surrounds it (display all cells around it and continue this using recursion)
- Allow the player to click on a cell in the GUI and display the neighbor count (or lose the game if it was a mine)
- Allow the player to flag cells
- Winning/Losing a game when all cells that aren't mines have been visited
- Timing the game
- Calculating a score based off of selected difficulty and amount taken to win (Not implemented yet) and storing this in a file for high scores
