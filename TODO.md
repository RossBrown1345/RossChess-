### TO DO:

~~ make chosen piece move to new destination ~~

~~then hang fire on GUI, work on possible moves for each piece~~

# known problems:


removing invalid moves will only remove every other invalid move, investigate, remove()
maybe accumulate invalid moves then remove as a list

# possible moves for

~~pawns~~
~~horses~~
~~bishops~~
~~rooks~~
~~queens~~
~~kings~~

~~return to GUI to allow for selection of pieces and highlighting possible moves~~

~~allow pieces to be moved with clicks~~


~~gameplay loop~~

~~score keeping~~

~~check when game over~~


### king in check
x bases to cover

~~detect if the king of the current turn is in check, covers discovered check~~




# must move out of check if in check

# other piece can block check

can fell both of these at once, if king is in check, when selecting a piece and getting possible moves,
remove all moves that dont set check to false. these are done, just need to update cyan moves

# must not move into check,


castling
~~promotion~~
en passant



make main menu for pvp or pvJoshua

improve sprites

Joshua : 

minimax
AB pruning
opening book
iterative deepening
identify forks
depth 1 reordering


add extra pygame panel to show game clock, and score difference, aswell as whos turn it is
add pygame panel to allow promotion options


