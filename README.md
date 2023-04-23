# Tic-Tac-Toe-game-in-python
Tic Tac Toe is a simple 2-player game on a 3x3 grid. Players take turns marking a cell with 'X' or 'O' to get 3 in a row, column, or diagonal. Python implementation involves a matrix to represent the board, functions to check win/draw and display the board, and a main loop to take turns and check results.
To create a Tic Tac Toe game in Python, we start by defining a 3x3 matrix to represent the game board. We then create functions to display the board, check for a win or draw, and implement the main game loop.

The display board function prints the current state of the game board in a user-friendly format, with symbols in each cell indicating which player has marked it or if it is still empty.

The check win function determines whether a player has won the game by checking for three matching symbols in a row, column, or diagonal. If a winning combination is found, the function returns True; otherwise, it returns False.

The check draw function checks if the game has ended in a draw by checking whether all cells have been filled without a winning combination.

The main game loop allows players to take turns making moves on the board. After each move, the loop checks for a win or draw using the functions defined earlier. If a player has won or the game has ended in a draw, the loop terminates and the result is displayed.

Overall, the Tic Tac Toe game in Python is a fun and easy project for beginners to practice their programming skills. It involves basic concepts such as functions, loops, and conditionals, and can be customized to add more features or graphics to make the game more enjoyable.
