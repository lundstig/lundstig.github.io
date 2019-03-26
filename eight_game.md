# Eight Game
[Kattis Link](https://po.kattis.com/problems/attaspelet)

*The Eight Game* (a smaller sibling of the more known 15-game) is a type of puzzle that consists of 8 square blocks in a frame. The blocks are numbered from 1 to 8. The frame fits 3 * 3 = 9 blocks, so there is a free spot. One move consists of moving *one* neighbouring block into the free spot. Write a program that calculates the smallest number of moves required to reached the ordered state shown to the right in the figure.

Tips: All test cases are solvable, and solution never requires more than 31 moves.

## Input
You will get a line with 9 integers, where 0 represents the free spot.
The numbers are given top line first, from left to right. Each number between 0 and 8 will appear exactly once.

## Output
Print the samellest amount of moves required to get to the ordered state, from the given start state.
