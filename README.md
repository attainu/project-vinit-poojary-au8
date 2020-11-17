# Problem Statements: Chess LLD

## Usage
First clone the project
```
git clone https://github.com/attainu/project-vinit-poojary-au8.git
```
* And open chess.py hit run to start playing 
* State a move in chess notation (e.g. A2A3). 
* Note - Add starting point and end point to move piece. 
* Type "e" to exit.

## Entities
If you have already played it already then you might already know this. But to ensure that we all are on the same page, I am defining some here:
* Board: Board is the one entity representing an actual board on which you play this game.
* Cell: A board consists of a grid of cells.
* Player: Someone who is actually playing right.
* Piece: There are various types of pieces as explained below.

## Pieces and their moves:
* King: Key entity in chess. If your king is killed then you lose. Its also called checkmate.
* Queen: It can move any number of steps in a single move and in any direction.
* Rook: It only moves in horizontal and vertical direction but can move any number of steps in single move.
* Bishop: It only moves in diagonal direction but can move any number of steps in single move.
* Knight: It makes L shaped moves. Check online for more details about it.
* Pawn: It can move 1 step forward vertically. If it is its first turn, then it can also choose to make 2 steps in single move.  
Note: All pieces except Knight cannot jump any other piece. Knight can jump over other pieces.
