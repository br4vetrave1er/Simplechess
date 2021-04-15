## Chess AI

Simple Chess is one player chess game created using c++.

- It's a console based game
- user can play as a black or white.

## Images

![Image](https://github.com/inDefinate9/Simplechess/blob/main/Screenshot%20from%202021-04-08%2005-53-37.png)

![Image](https://github.com/inDefinate9/Simplechess/blob/main/Screenshot%20from%202021-04-08%2005-53-54.png)

![Image](https://github.com/inDefinate9/Simplechess/blob/main/Screenshot%20from%202021-04-08%2006-01-57.png)


## Todo

- Download the zip file.
- After extracting file compile the program using c++ compiler.

  eg. If you have g++ compiler then  "g++ -o chess chess.cpp"
- Run the compiled c++ program "./chess"

## Commands

- ?/h/help : Shows the list of all the commands avialable.
- q : Quit the game.
- p : Printing the board on screen.
- c(Toggle) : Show coordinates of all the squares.

## Input

- User inputs the move in "****" from where First two digits show the starting coordinates and last two for destination coordinates.
- eg. "1718" : move the peice on coordinates "17" to "18".

## AI
  Minmax Algorithm is used by the coumputer. In this recursive tree of all possible moves are explored to a given depth and the position is evaluated at the leaf. After that we return depeding on wheather its whites turn or black we try to maximize the value (if White) or minimize (black) from the root node to parent node.

## Issues
- No castling
- no En passant
- no pawn promotion
- naive minmax implementation
- UI
