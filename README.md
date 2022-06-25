# PPS-Sem-End-project
This is my semester end project for my Programming for Problem Solving class. I have made a stone paper scissor game, that leaves the total tally of wins, losses and draws in a text file for each session.
My project is a small game of stone, paper, scissors that can be played for entertainment. We have defined a function called “game()” that compares the niput of the user and computer to determine wether the round is a win or a loss. In the main function, we use the rand() and srand() functions of the stdlib.h header file to make a random number generator that is used to determine the computer’s input for the game. The srand() function is being used with argument ‘time(null)’ to change the seed for the rand() function continuously in relation to the system time so that the computer’s input does not come out the same every time.
We take the output of wether you win or lose or draw in a file called “score.txt” and thw output of how many games you have won, lost and or drawn in another file called “counter.txt”.
Header files used:
o	Math.h
o	Stdio.h
o	Stdlib.h
o	Time.h
