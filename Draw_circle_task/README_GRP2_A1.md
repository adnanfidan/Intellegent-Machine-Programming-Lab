## Group Members
Dorian Fülöp
Jiabao Song
Adnan Fidan
Rui Tu

## Contents
UR teach pendant video
RoboDK video (could not save the file for upload due to trial version of RoboDK)
forcegroup2.urp		
group_2.installation


# Drawing a Circle with teach pendant and RoboDK
1) define home point in base frame
2) define and moveJ to entry point in base frame
3) define and moveJ to approach point in base frame 
4) define and moveJ to touch point in base frame 
5) use touch point as starting point in whiteboard frame
6) define via point in whiteboard frame
7) define end point in whiteboard frame
8) draw semi-circle with unconstrained circlemovement function in whiteboard frame
9) repeat steps 5 to 8 for the second half circle with appropriate new points

For RoboDK, first define the whiteboard frame and then perform the same steps as above but with MoveC function for drawing the semi-circles. 





