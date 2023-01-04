# Explanation

This problem is solved using Linear Approach.

list of blocks and list of requirements are passed as a parameter to the ApartmentHunting Function.

We calculate no of moves for each block to fulfill the requirements.

In NoOfMoves Function, we have current block index, list of all block details and list of requirements.


We get the no of moves to fulfill the requirements by calculating 

 
  1.the possibility to fulfill the requirements from top to current block and get no of moves
.    
  2.the possibility to fulfill requirements from current block to end of block
.   
  3.the possibility to fulfill the requirements by going up and down from current block
.

After getting Number of Moves form single block in different direction, we return the lowest number of moves and save it in a object.

After getting Number of Moves for each block, we group it by the number of moves and return the first of list of blocks with the lowest number of moves.
