
## Phase 0: Selection, Analysis & Plan

#### Selected Project: Breakout/Arkanoid Style Game

### Necessary Features
What are the core features that your program should have? These should be things that __must__ be implemented in order to make the program useable/playable, not extra features that could be added to make the program more interesting/fun.
- a controller paddle
- mouse tracking
- rows of bricks
- a ball that bounces off surfaces
- ability to lose a life if the paddle misses the ball
- coloring of objects
- second level, 2-3 total 
- ball inc speed
- ability to reset and pause the game. 

### Extra Features
What are some features that are not essential to the program, but you would like to see (provided you have time after completing the necessary features. Theses can be customizations that are not part of the core requirements.

- create 2 balls on upper levels
- require multiple hits on bricks as levels progress

### Array Usage
How will you be using arrays in this project?

1D Array:
- set the rows of bricks in the game

2D Array:
- determines if ball shares same x/y cor as brick

### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.

Keyboard Commands:
- keyPressed() -->
- Space bar to start game (ball movement)
- 'R' for reset
- 'P' to pause game

Mouse Control:
- Mouse movement: mouseMoved() --> paddle , mouseX 
- Mouse pressed: mouseClicked() 


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

Ball 
- Instance variables:
  - x
  - y
  - xSpeed
  - ySpeed
  - new ball
- METHODS
  - display
  - constructor
  - collide
  - bounce

Paddle 
- Instance variables:
  - x
- METHODS
  - constructor
  - display

Bricks
- Instance variables:
  - rows/columns
- METHODS
  - constructor
  - display 
