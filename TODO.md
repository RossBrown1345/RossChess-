### TO DO:

diversify opening book

update sprites

add main menu screen

add game timer and score counter

have another crack at check

# known problems:



# Opening book
have each line be an [array] with "name", length of seq, ((seq))
before each move, run a depth 2 minimax to check for immediate danger

# add promotion (and for Joshua)
promotion functionality already works
have discrete non possible values for these moves
when in movepeice have check for special move
perform extra changes to the supplied gamestate


# add castling (and for Joshua)
have checks for all preconditions (bar being in check)
then have function to change supplied gamestate

have discrete non possible values for these moves
when in movepeice have check for special move
perform extra changes to the supplied gamestate






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

# gameplay

make main menu for pvp or pvJoshua

improve sprites

Joshua : 

~~minimax~~
~~AB pruning~~
opening book
iterative deepening
identify forks
depth 1 reordering


add extra pygame panel to show game clock, and score difference, aswell as whos turn it is
add pygame panel to allow promotion options


