# Stable-Marching
This is an implementation of a solution to the Stable Matching from the general pseudo-code on Wikipedia. It is specifically written for the 1 and 10 pairings for Purdue's AAMB. 

Input file must be in the format:

> 1,Person1,choice1,choice2,choiceN

> 1,Person2,choice1,choice2,choiceN

> 10,Person3,choice1,choice2,choiceN

> 10,Person4,choice1,choice2,choiceN


With a total of N choices for each person and 2N total lines.

Program Execution
-----------------------------------------------------------------------------------------------------------------------------------
Be sure to update the global constant, PAIRS, in matching.cpp before compiling.

After cloning and compiling, run
> make

in the same directory, then
> ./Matching filename
  
where filename is a text file that follows the specifications above.
