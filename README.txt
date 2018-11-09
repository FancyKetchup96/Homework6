To change the starting position of the pegs, change lines 8 and 60.
In line 8 change the 1 in [1] to whatever number you want to start as empty, put 1, at the beginning of the list, and remove the starting position from the list.
For example if you want to make the starting position 2:

	play([2], [1,3,4,5,6,7,8,9,10,11,12,13,14,15], [], Moves).	%MAKE CHANGES HERE

In line 60 change the number from 1 to whatever you want the starting position to be.
For example if you want to make the starting position 2:

	display(Sol, [2]).
