# C++-game-of-life

The Game of Life, invented by John H. Conway, is supposed to model the genetic laws for birth, survival, and death. We will play the game on a board that consists of M squares in the horizontal direction and N squares in the vertical direction (0<M<40, 0<N<40).  Each square (except for border squares, on the edges of the board) can be empty or can contain an X indicating the presence of an organism. Each square (except for border squares) has eight neighbors. The next generation of organisms (the next turn in the game) is determined according to the following criteria.

a)     Birth – an organism will be born in each empty location that has exactly three neighbors

b)     Death – and organism with four or more organisms as neighbors will die from overcrowding. An organism with less than two neighbors will die from loneliness

c)     Survival – an organism with two or three neighbors will survive to the next generation.

d)     Assume that the borders (where squares have fewer than 8 neighbors) are infertile regions where organisms can neither survive nor be born. Thus, border squares will always be empty.


·      a global constant will be used to define the maximum size of the two dimensional arrays

·       The names of the input data file and output file are supplied by the user as keyboard input.

·       The initial configuration of organisms is provided in an input data file.

o   The first line of the input data file contains three integers. These three integers represent

      §  The number of rows in the game board

      §  The number of columns in the game board

      §  The number of generations to be calculated (the initial board is generation 0, the first new generation calculated is       generation 1)
