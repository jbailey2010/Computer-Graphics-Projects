Instructions/general information on mp2

Rotation (pitch/roll/yaw) is done with a complex vector system class, a normal vector class, and a camera object that keeps track of its own position and direction. All in one file. I know that's frowned upon, but to one-up that, I copy-pasted mountain.cpp into here, so I went all out on bad style in that regard.

The code is all in bailey27_mp2.cpp

Controls are:
These are the controls I added because I'd like 5% extra, or quite possibly misread the instructions. Regardless, that's a win-win as I'd cover everything at worst, but at best earn extra credit
u   Speed up
d   Slow down
l   Yaw/Rudder left
r   Yaw/Rudder right

These are the required implementations
up      Rotate up
down    Rotate down
left    Rotate left
right   Rotate right


Directions to run it are very simple:
 make will compile it
./mp2 should run it, despite it being in bailey27_mp2.cpp


Added after reading comments on mp1 grading:
Written and compiled on the siebel linux computers.
