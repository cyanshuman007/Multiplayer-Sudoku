# Multiplayer Sudoku
The version of Sudoku allows multiple players to work on the same puzzle.  It is written in Java Swing.
 
## Features
* Allow a host to start a Sudoku puzzle
* Allows multiple guests to join the host to work on the puzzle

## Technical design
* Uses Swing to draw the board and gridlines
* Uses a basic backtracking algorithm to generate a puzzle
* Will switch to the [Dancing Links algorithm] (https://www.ocf.berkeley.edu/~jchu/publicportal/sudoku/0011047.pdf) to generate a puzzle

## Screenshots
![screen] (/screenshots/sudoku-host.png) ![screen] (/screenshots/sudoku-guest.png)

## License
Released under the [MIT License](http://creativecommons.org/licenses/MIT/).
