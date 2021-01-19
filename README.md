This was the set of files given to me for week 3 of the MIT xpro course.
Most of the files were already finished and used for learning. The files I worked on were those in the Next Tech folder as well as the 
bigBang.html. The original bigBang file generated a certain number of balls set by the user and had them assigned a random whole number for the x and y velocities. The update() function would make the balls move outward from their starting position in the center of the area.

I made the velocites random floats instead to actually randomize movement of the balls. I created an empty array for colors and had the factory() function create a number of randomly generated colors to fill in the array that matched the total number of balls generated. I then had the update() function make a static ball at each location the balls went through to make a trail. 

When the program is loaded it will autmatically create a random number of balls, assign a random color and random x/y velocities. Refresh to have more fun!


# Practice Javascript Coding

Notice how we load other files into our code. eg mystyles.css and ball.js. Sometimes we do this to "hide" complexity. Here we are hiding the complexity of dealing with the browser memory by putting that in ball.js.

## Projectile.html

This allows you to create balls that move under gravity. They will bounce off the walls.
Understand how to create a ball at a specific location. Also to give it a velocity that varies under gravity.
Understand how arrays are used to store lots of balls.

## Randomwalk.html

This explores how molecule move randomly.
We investigate a "sneeze"
Can you add gravity so the virus particles drop to the ground?

## Randomwalk2.html

Here we add tracking of the particles. How do we do this? It seems "wasteful" to create lots of copies of the particles. However, in the browser its the only way.

## string.html
