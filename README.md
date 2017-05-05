# tictactoe
A silly, super simple, little text-based tic tac toe, written in Python. 

The "board" is just a string in this format 

```
  a b c
x . . .
y . . .
z . . .
```

Player 1 (as `0` in the program, playing using the symbol `o`) and Player 2 (as `1` in the program, playing using the symbol `x`) takes turn to fill the board, telling the program which part of the grid to fill using horizontal-vertical notation (`ax` is top-left, `by` is the center, for example). Whoever gets three in a row wins.
