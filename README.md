# PegGame
Peg Game is most commonly played on a triangular board that contains 15 holes and 14 pegs. The 14 pegs can be placed in any order on the board. Therefore, the initial state would be 14 pegs placed into the holes, with one hold remaining empty. Consequently, the goal state is when only one peg is left remaining on the board, in any hole.
The challenge of the game comes in avoiding stranded pegs. If, at any point in the game, there is a stranded peg that cannot be jumped over, and the total number of pegs still in play is not equal to 1, the game ends and the player loses. The only way to win the game is to have a single peg remaining on the board with no stranded pegs.
The AI plays the game using A* search
