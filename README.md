Tic Tac Toe in Python

This is a simple command-line Tic Tac Toe game implemented in Python. The game allows two players to play against each other by taking turns.
Features

    Two-player game
    Simple command-line interface
    Automatic win and tie detection

Requirements:

    Python 3.x

How to Run

Clone the Repository:

    git clone git@github.com:MazibukoLindokuhle/Tic-Tac-Toe-Python.git
    cd Tic-Tac-Toe-Python

Run the Script:

    python tic_tac_toe.py

How to Play

    The game starts with an empty 3x3 board.
    Players take turns to make a move. Player 1 uses "X" and Player 2 uses "O".
    To make a move, enter the row and column numbers (0, 1, or 2) separated by a space.
    The game continues until there is a winner or the board is full (resulting in a tie).

Example Gameplay:


  |   |  
-----
  |   |  
-----
  |   |  

Player X, enter your move (row and column): 
0 0
X |   |  
-----
  |   |  
-----
  |   |  

Player O, enter your move (row and column): 
1 1
X |   |  
-----
  | O |  
-----
  |   |  

Player X, enter your move (row and column): 
0 1
X | X |  
-----
  | O |  
-----
  |   |  

Player O, enter your move (row and column): 
2 2
X | X |  
-----
  | O |  
-----
  |   | O

Player X, enter your move (row and column): 
0 2
X | X | X
-----
  | O |  
-----
  |   | O

Player X wins!

Code Structure:

    print_board(board): Function to print the current state of the board.
    check_winner(board): Function to check if there is a winner.
    is_board_full(board): Function to check if the board is full (tie condition).
    main(): Main function to run the game loop and handle player moves.

License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.
