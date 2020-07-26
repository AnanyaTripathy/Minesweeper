# Minesweeper
1.Goal of the game is to find all mines on the board.
2.You reveal mines by clicking at board field.
3.If you reveal a field with mine you lose the game.
4.If you reveal field without a mine it will show exact number of mines surrounding that field.
5.If you reveal field without number it means that there are no mines in its surroundings. In that case board will reveal all connected empty fields with its surroundings.
6.You can flag field by right-clicking it.
7.If you click on a revealed field and you already flagged all mines around that field, board will reveal rest of the hidden fields. 
Of course, if you misplaced flags you will reveal a field with a mine and lose the game.

Differences from classic
------------------------
 * left-right click to reveal neighboring cells is now triggered with left click only
 * left click on a revealed cell with exactly as many neighbors as its number will automatically flag neighbors
 * cheat mode - click bottom left of game to reveal all mines
 
todo
----
 * add icons for mines, flags, and start button (win, lose, reset)
 * **hint system** - when stuck, point out rules that can be applied
 * **evil minesweeper** - for uncertain situations, always set the mines to be where the user clicked
 * **good minesweeper** - in a situation where no mines can be flagged absolutely, reveal a mine
