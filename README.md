### Knight's Tour Game

The Knight's Tour is a classic chess puzzle where the objective is to find a sequence of moves for a knight to visit every square on the chessboard exactly once. In this implementation, I have created an interactive python program to play the Knight's Tour game.

### How to Play

1. The chessboard consists of an `8 x 8` grid.
2. The knight starts from a given initial position on the board.
3. The objective is to move the knight in such a way that it visits each square on the board exactly once.
4. The game continues until the knight has visited every square or can no longer make a valid move.

### Interactive behaviour

Users have to enter numbers instead of the chess coordinates. The mapping is as follows:
```python
a1 --> 01
b1 --> 02
h1 --> 08
a2 --> 09
h8 --> 64
```
After each move made by the user, a list of all the remaining legal and valid moves for the knight is displayed from which the user can choose the next legal move.