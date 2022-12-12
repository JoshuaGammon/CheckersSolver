Checkers Solver

This project was a group effort by Joshua Gammon, Kinsey Neas, Marcos Morales, and Sean Stepanik.

After calling make, you can call -h or --help for a list of commands.

The interactive game is still a work in progress, but the project has the functionality of:
-deciding the best move by evaluating _every_ possible move (and all moves that will come after). Do not call this on a board with many possible moves. It will never finish.
-deciding the best move based on a decided cut off depth. The default is 4 (the computer will look 4 moves into the future), but one can change this per move using -d and putting an integer.
-making moves on the board.
-printing out the board.
-describing how good a move is.
