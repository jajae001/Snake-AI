# SNAKE GAME AI - Unity

#The idea is to create a Game ai to complete each level of the Game.
#To provide the Ai with as many choices as possible, I intended to start the coding by building a behaviour tree that primarily used selectors rather than sequencing. 
#As I didn't want the AI to make decisions at random, I began by establishing a new Selector and setting it to false. 
#I then provided the AI with new conditions to filter, beginning with determining whether there were impediments in the AI's path and turning away from them.
#In order to find where the food would be in the future using code that tries to avoid the snake body, a new filter utilising Raycasting was then introduced.
#The AI was then adjusted using a filter that performed pathfinding after this, first determining if the food was reachable.
 
![image](https://user-images.githubusercontent.com/77746546/218153201-e943429f-140c-47ef-80ac-8a27fc0e8e91.png)
