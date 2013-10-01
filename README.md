Group24
=======


			                                PROCESS SYNCHRONIZATION

DINING PHILOSOPHER

Five silent philosophers sit at a table around a bowl of spaghetti. A fork is placed between 

each pair of adjacent philosophers. (An alternative problem formulation uses rice and 

chopsticks instead of spaghetti and forks.)
Each philosopher must alternately think and eat. However, a philosopher can only eat 

spaghetti when he has both left and right forks. Each fork can be held by only one 

philosopher and so a philosopher can use the fork only if it's not being used by another 

philosopher. After he finishes eating, he needs to put down both forks so they become 

available to others. A philosopher can grab the fork on his right or the one on his left as they 

become available, but can't start eating before getting both of them.
Eating is not limited by the amount of spaghetti left: assume an infinite supply.
The problem is how to design a discipline of behavior (a concurrent algorithm) such that 

each philosopher won't starve; i.e., can forever continue to alternate between eating and 

thinking assuming that any philosopher cannot know when others may want to eat or think.


HOW TO USE :

 To run the application Open the DPS.application or criticalsectionproblem.application or 

dps1.0.application .

After opening the file use the process buttons to operate through the applications.
