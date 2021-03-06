# Python-Cellular-Automaton

The program generates Game of Life cellular automaton.

For information on the origins of this type of cellular automaton click **[here](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)**.

100 matrices (generations) of 100 x 100 dimensions store values of 1 (alive) or 0 (dead) based on an initial condition and the application of the rules of Game of Life. 

(1) Any live cell with two or three live neighbours lives on to the next generation\
(2) Any live cell with fewer than two live neighbours dies, as if by underpopulation\
(3) Any live cell with more than three live neighbours dies, as if by overpopulation\
(4) Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction

The matplot visualizations of each matrix are saved as .png files and then used to generate a .gif file.

Each cell in a generation subsequent to the initial condition is determined to be alive or dead based on the sum of the 8 adjacent cells (count of alive neighbours) of the preceding generation. For more details refer to the python notebook **[here](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/game_of_life_08.ipynb)**. 

Below are sets of three images of the initial condition, 50th generation and the final 100th generation. Click the inital condition title to view the animation. 

**[Random Cells](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/GIFs/game_of_life_01.gif)**

![alt text](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/Images/Test01_RandomCells.JPG)

**[Random Row](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/GIFs/game_of_life_02.gif)**

![alt text](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/Images/Test02_RandomRow.JPG)

**[Random Cells 10% Chance Initially Alive](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/GIFs/game_of_life_03.gif)**

![alt text](https://github.com/aaronmkwong/Python-Cellular-Automaton/blob/main/Images/Test03_RandomCells10.JPG)
