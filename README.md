# Web2048
follow imooc &amp; add something new

## Screenshot:
![](https://github.com/yxfanxiao/Web2048/raw/master/screen.png)  

##My Note:
####1. init the container: contain 4*4 cells
	grid-cell: empty cells
####2. init the game
	confirm the position of each grid-cell
	after each handle,updateBoardView
		remove all
		when 0 place at the grid-cell center with 0px heigth&width
		when value not 0 cover the grid-cell with the number-cell, change number color&background color
			number-cell: cells with value
	generateOneNumber * 2
		when have empty cell random 2 | 4 at random position
			animation: in a cell number generate from a piont to a whole cell
####3. keydown
	up,left,right,down	
	example:Up
		lock the scroll bar
		moveUp
			canMoveUp
			move
				animation: move from one cell to another cell
				ConflicteFlag
			updateBoardView
		generateOneNumber
		####judge isgameover()


