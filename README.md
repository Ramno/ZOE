# ZOE or Zombie Out Break Emulator

Project Summary
ZOE simulates the spread of zombies across a world filled with non-player controlled elements (NPC) that are composed of humans and zombies. Humans will navigate the world trying to survive for as many days as possible while hunting for supply depots that restores their health, prevent them from starving to death and increase their attacking power against zombies. Zombies navigate the world hunting for humans to eat and turn them into other zombies. 

How the simulation is set up?
Users do not have the ability to control the action of each NPC. Users can only set the type, number, and location of each element. Then the world will randomly generate these elements and they will behave by themselves. 

What are the different types of NPCs and their attributes in the simulation? 
Humans
Attack Power: Chance of surviving a fight
Health: Hit points for survival
Hunger: Count down timer until the health begins to decrease automatically
Sensor: Detection of other NPCs
Speed: how quickly a human moves throughout the world 
Morality: Chance of fighting another human

Zombies
Attack Power: Chance of surviving a fight
Health: Hit points for survival
Hunger: Count down timer until the health begins to decrease automatically
Sensor: Detection of other NPCs
Speed: how quickly a zombie moves 
Rage: How long will a zombie chase a human that it encounters?

Supply depot
Randomly restores or adds point to attack power, health, hunger, for human NPCs.

What happens during a simulation?
Each NPC will randomly move throughout the world and encounter other NPCs. With each encounter, several possibilities may occur:

If a human meets another human
1.	Nothing happens
2.	They fight
a.	One will gain/lose points in their attributes and they escape from each other
b.	One or both will die

If a zombie meets another zombie
1.	Nothing happens

If a human meets a zombie
1.	Zombie dies and human gain/lose points in attribute
2.	Human runs away
3.	Human dies and becomes a new zombie

If a human meets a supply depot
1.	Random point increase in attribute points

How does a simulation end? 
Simulation ends when there are no more zombies or no more humans!

How does a

