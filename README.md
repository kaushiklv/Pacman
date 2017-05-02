# Pacman

A project on reinforcement learning applied to the game of Pac-Man.

I have applied Q-Learning Algorithm in this project to Pac-Man which learns to play the game very optimally 
within a few episodes of training.

My contribution to this project is the implementation of the algorithm. 
I got the code base / starter code for this project from the course "Intro to AI" by UC Berkeley. Kudos to them for this!
Interested people can download this code base for thier own enhancements from the following link - 
http://ai.berkeley.edu/reinforcement.html#Q7

Execution Procedure - 
Once you are in the directory of the project use the following command - 

python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic 

Here 50 is the number of training episodes and once this is done it will run simulation (60 - 50) = 10 times for you to see 
and observe the results of training.

You can also change the size of the grid to any one of the following - 
(1) smallGrid
(2) smallClassic
(3) mediumGrid
(4) mediumClassic
(5) originalClassic
(6) trappedClassic
(7) trickyClassic
(8) openClassic
(9) contestClassic
(10) capsuleClassic
