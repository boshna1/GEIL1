Joshua Dinata
100921955

Target Practice 
Game spawns targets in which the player simply left clicks to destroy them, the player also have ability to move around and look around. The player wins when destroyed 30 targets, but there is a chance that less than 30 spawn!

Flowchart: https://www.canva.com/design/DAGzdKmG5qU/ilIvb6C8S5qkEpeQdrIEpQ/edit?referrer=flowcharts-landing-page

Reflection:
The system I have that uses Singleton is Score and Target spawn

For score, I used singleton because I only need one intance of the system to exist to store score values. By having it as a singleton it also gives possiblity to exist between levels, keeping information of score available if needed in a previous or next level.
I also have target in Singleton because I only need one instance of the system to spawn currently for initialize of the game.

I think singletons are beneficial to these systems because it makes the flexibile for use in other level, rather than keeping them contained in a single level. Also having it as singleton makes it globally available and won't be destroyed on loading another level.
