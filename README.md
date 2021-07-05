# Minesweeper-Project


Introduction:
                  Minesweeper is a single-player game in which the player has to clear a square grid containing mines and numbers. The player has to prevent himself from landing on a mine with the help of numbers in the neighbouring tiles.
Compiler : 
               Jupyter Notebook (Anaconda) python version 3.6
Helping material :
                     Github / Youtube / Stackoverflow
Prerequisites:
Here are some prerequisites that you should know before moving forward with this article:
•	understanding of string, int data types
•	understanding of list data structure
•	understanding of conditional statements
•	understanding of for, while loops
•	understanding of multi dimensional arrays
•	understanding of declaring and using functions
•	understanding of using list comprehension


Procedure:
	We have defined many functions one of them is board function.
	 First we made a board. Next step was to make a function for bombs and how to plant them, defining the rows, columns and size of the board.
	 Then we defined some values in recursive function so that while playing the game board can check the bombs.
	 We set up the positions of the mines randomly, so that the player might not predict their positions.In the code, we choose a random number from all possible cells in the grid.
	 We keep doing this until we get the said number of mines. For example, our input is 1,1, it will check the bombs present in the neighbouring row and column like 1,2 or 1,3.
	The numbers on the board represent how many bombs are adjacent to a square. For example, if a square has a "3" on it, then there are 3 bombs next to that square. "*" represents the bombs in our program.
	 Then we printed the board so that we can get a visualisation how does the board look like, we made it visible so that while playing the game we can see a board on desktop. 
	We used string function so that when we run it says Enter the input in terms of rows and columns.
	 At the end we used play function so that it directly can show the game rather than showing all the inputs and outputs.
	 Lastly it was difficult, we faced many problems and for that we took help for different platforms such as Youtube and Github
