Tic Tac Toe

A basic application using React.js to implement Tic Tac Toe board game.
Taskflow followed in devloping this project:

- Create a base Raect App.
- Add a new component in 'src' as "Board.js"
- Add a table in 3X3 in "Board.js" to show a TicTacToe board.
- Use a 'num' as a prop to get cell index being clicked.
- Define char Array of 9 cells to store Move data.
- Define checkWinner() to match moves in 8 different patterns for a win, i.e. Across(3), Down(3) and Diagonal(2).
- Define a function handleClick() to-
  -> Set move in table/board/Array using state. Display the same on board.
  -> Keep tab of rotating turns after each move.
  -> Check for winner after each click event via calling checkWinner().
- Declare winner if game is won.
- Provide an option to playAgain() or Exit() the game.