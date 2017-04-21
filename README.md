# ZOE or Zombie Out Break Emulator

Project Summary

ZOE simulates the spread of zombies across a world filled with nonplayer controlled elements (NPC). 

----------------------------------------------------------------------------------------------------------------------------------------

What can a user do? 
Users do not have the ability to control any individual NPC elements. The user will only determine the type and number of each elements prior to the beginning of each simulation. Once the simulation begins, the user can take no further actions.

----------------------------------------------------------------------------------------------------------------------------------------

What happens during a simulation?
each NPC will randomly move throughout the world and encounter another NPC. With each encounter, several possibilities may occur:

If an uninfected meets another uninfected
1) nothing happens
2) One uninfected fights another
 a) gain/lose health
 b) gain/lose morality point
 c) gain/lose attack power
 d) death/no death
3) forms a "group" and then group travels together

if an uninfected meets an infected
1) infected dies 
 a) lose health/attack power for uninfected
2) uninfected dies and a new infected is created
 a) stats for new infected is reset to 0

If an uninfected meets a supply depot
 1) health is restored to full
 
Simulation ends when there is no uninfected OR infected NPCs. 

----------------------------------------------------------------------------------------------------------------------------------------
NPC ELEMENTS

Elements include uninfected and infected persons. Each element will have certain attributes that determines the probability of surviving an encounter with another element. 
Uninfected Attributes

Attack Power:  
Health: 
 

Infected Attributes
-------------------------
Attack Power:
Health
Rage

Future Capabilities:
Teamwork: chance for uninfected to band together 
Morality: chance for uninfected to turn on and betray another uninfected

