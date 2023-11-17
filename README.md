# sta308_midterm2

Title: STA308 Midterm 2
Author: Will Paz

The following details the assignment for the second midterm of STA308. We are delving into simulating the results of either choosing to take a two point or three point shot to end a game while down by one point. I hope you enjoy the commentary as well as the code itself. 

Preface:

Stated Problem

As coach, you get to decide: does your team go for a two point field goal or a three point field goal? Your code must consider both scenarios.

Going for two
When you go for a two point field goal, there is a 65% chance your team completes the inbound pass (so 35% chance it is stolen and you lose the game). The player who receives the ball has a 52% chance of making the shot (you are awarded 2 points, and win the game). There is a 10% chance that player is fouled on the play.  If fouled, they are awarded two foul shots and unfortunately are not a good shooter -- they have a 55% chance of making each shot (each worth one point, so you may miss both, make one and tie or make 2 and win the game)).  So by using this strategy it is possible your teams scores 0, 1 or 2 points, but the outcome is randomly determined by probabilities.

Going for three
When you go for a three point field goal, there is an 80% chance your team completes the inbound pass. The player who receives the ball has a 40% chance of making the three point shot (you are awarded 3 points, and win the game). There is only a 5% chance they are fouled on the play. However if fouled, they are awarded three foul shots and because this person is a good shooter, they have an 95% chance of making each of the foul shots (so they may make 0, 1, 2 or all 3 shots).  The possible point outcomes from this strategy are 0, 1, 2, or 3 points but again random. You will win the game if your team scores 2 or 3 points. 

Which scenario is the better decision?

