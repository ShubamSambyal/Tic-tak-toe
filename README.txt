--------------------------------------------------Working of the COde--------------------------------------------------------------

1.The TicTacToe class is initialized with the grid size n and win streak m.
2.The print_board method prints the current state of the board to the console.
3.The make_move method updates the board with the player's move. If the move is invalid (i.e., the cell is already occupied), it returns False.
4.The check_win method checks if there is a win condition on the board. It checks rows, columns, and diagonals for m consecutive marks.
5.The play_game method runs the game loop. It prompts the user for input, updates the board, and checks for a win condition.
6.In the if __name__ == "__main__": block, the user is prompted to enter the grid size and win streak, and a new game is started.


----------------------------------------The Things i have changed are as follows----------------------------------------------------

1.I added a GUI using Tkinter to create a responsive and playable game on both desktop and mobile devices.
2.I added input validation to ensure that the user enters a valid grid size and win streak.
3.I implemented the game logic to handle turns, check for a win or draw, and display the result.
4.I added a game_over method to disable the buttons and display a "Game Over!" message when the game is won.