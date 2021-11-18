# inda-prolog-go
The assignment is to implement a function (called a predicate) in Prolog that calculates whether a group is alive or dead in the game of Go https://en.wikipedia.org/wiki/Go_(game). 

A group is defined as one or more stones of the same color that are horisontally or vertically adjecent to eachother. 
If two stones share an adjacent stone of the same color they are considered to be part of the same group. 
A group is alive if it has atleast one liberty. A liberty is a horisontally or vertically adjacent spot on the board that isn't covered by another stone. A stone at the edge of the board is considered to have one less liberty. Coversely, a stone at the corner of the board is considered to have two less liberties. 

The function only needs to be able to handle boards of size 9x9, but it would be nice if it could handle bigger (or smaller) board sizes.

The file 'template.pl' contains a template for how to read input and a simple predicate that checks the position at (Column, Row) and returns true if it contains a stone.

There are two example boards that you can test your solution on.
