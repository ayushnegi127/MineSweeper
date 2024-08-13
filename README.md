Game - MineSweeper

Languages used- HTML,CSS,JAVASCRIPT

This code is a JavaScript implementation of the classic Minesweeper game. Here's a brief explanation of its functionality:

1. A grid of 10x10 cells is created in the HTML document.

2. The player can click on cells in the grid to reveal what's underneath.

3. The game randomly places 20 mines in the grid. The mines are hidden from the player.

4. The player's goal is to reveal all cells that do not contain mines.

5. When a cell is clicked, the init function is called, which performs several tasks:

   .It checks if the game is already completed (won or lost), and if so, it doesn't allow further interactions.
   .If the clicked cell contains a mine, all mines are revealed, and the game is locked, indicating a loss.
   .If the clicked cell doesn't contain a mine, it:
   .Marks the cell as "active."
   .Displays the number of mines in adjacent cells.
   .If there are no adjacent mines, it recursively reveals neighboring cells without mines.
   .After each click, it checks if the game is complete by verifying if all non-mine cells are revealed. If so, it alerts the player that they have found all the mines.
   .The revealMines function highlights all mine cells in red when the game ends.

Overall, this code provides the core functionality of a Minesweeper game, allowing players to click on cells to uncover mines and numbers, with the goal of revealing all non-mine cells to win the game.




