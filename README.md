## TraceBall 2018 Project One Version 1.0 - Luke Farren

## 1.0 Initiative

Design a 2d chase game coded with HTML, JavaScript and CSS that can be played within a web browser (Google Chrome, Mozilla Firefox, etc). in which a user box were to be controlled by mouse inputs and a AI box controlled by the computer chases the X, Y input of the users mouse until they collide causing the user to lose one of three lives until all lives are lost. 

## 2.0 Epics and User Stories
 
 **2.1 Epics**
 
 * Game based on HTML, JavaScript and CSS.
 * Playable in a Web Browser 
 * Game played with mouse input only
 * Computer enemy controlled by AI
 * Enemy must follow player piece. 
 * Enemy must be able to collide with player piece
 * User has 3 lives
 * Game ends when the user has zero lives left

**2.2 Non-Functional requirements** 

* Canvas size and colour. 
* Player size and colour.
* AI size and colour.
* AI player speed.
* AI enemy speed increases with every life lost.
* 

**2.3 User Stories** 

* As a player, I would like the enemy AI to chase my own game piece around the game area.
* As a player, I would like the enemy piece to collide with my piece causing me to lose a life.
* As a player, I would like to have clear instructions on how to play the game.
* As a player, I would like the game to display current lives
* As a player, I would like the game to display 'Game over' once all lives have been used.
* As a player, I would like a reset button to restart the game after losing.
* As a player, I would like a win scenario.
* As a player, I would like the game to be colourblind friendly.
* As a player, I would like all text to be legible.   

## 3.0. Genre

Browser based 2d chase game.  

## 4.0. Technical Details

##### Platform
Simple and free text editor Notepad was the only program allowed. 

##### Programming Language/Enviroment
The only language that was allowed to be used was HTML, JavaScript and CSS. 

##### Programming Challenges
* Small amount of knowledge of programming in general, with only a small amount of experience with C++, LUA and AHK. 
* Small amount of information given to start programming the game. 
* Different programming standards used when researching codes from different sources. 
* Steep learning curve and a different environment than familiar. 
* Creating the chase algorithm.
* Creating the collide algorithm.
* Small bugs in code without error messages. 


##### Constructing And Implementing Code
Task 1 - Understand how functions are written in JavaScript.

Task 2 - Research different coding practices used for JavaScript.

Task 3 -  Create a flow chart to show what needs to be written into the program and group them into function and algorithm blocks. 

Task 4 -   Set up a blank JavaScript session in Notepad which includes appropriate tags such as html, body style and script. 

Task 5 - Define a canvas with a border and background colour in the style tag. 

Task 6 - Add an appropriate title (h1), the rules/instructions (p1), a canvas div and a life counter div into the body on load tag.

Task 7 - Create different variables for each of the players and there X, Y coordinates and a game area variable. 

Task 8 - Create the canvas using the already defined canvas dimensions using document.getElementById and define how often the game area updates using setInterval.

Task 9 - Display the player square using the already defined player piece and its X, Y position variables using a function.

Task 10 - Get the player square to follow the mouses X, Y coordinates and hide the mouse cursor.
 
 Task 11 - Display enemy square using the already defined enemy piece variables and the X, Y variables using a function. 

Task - 12 Define player lives and enemy speed. 
 
 Task 13 - Use an algorithm to get the enemy square to move frame by frame towards the X, Y/player piece coordinates using the defined enemy speed.
 
 Task 14 - Set up a collision function between the two pieces when there X and Y coordinates match.
 
 Task 15 - Create a function to lose a life when the collision function requirements have been met this uses the already established enemy lives. 

 Task 16 - Create a function that ends the game and displays end game text.
  


##### Algorithms

An algorithm is used to control the enemy AI, for simplicity a frame by frame movement was used to determine the players piece, the enemy AI follows the X and Y position of the mouse input. Without prior coding knowledge this was the simplest method to implement. An algorithm was also used to determine how many lives the player has and has left, this included a feature that would speed up the enemy AI after every life lost, making it harder for the player. 

##### Coding Standards 

Effective coding standards where used during the construction of the code based on Google coding standards.

Indentation using the tab key was used for each new block of code, each indent is 8 characters long. 

Comments where used to explain each section of code.

## 5.0 Research

The main website used for research was [https://www.w3schools.com](https://www.w3schools.com/)


## 6.0 Project Management

##### Burndown Chart

https://github.com/LukeFarren/TraceBall/blob/master/Flow%20Chart.png

##### Flowchart



##### Functions

Multiple functions where used during this project, the first function used was for the player to be able to control the player piece using the X and Y inputs of the mouse. The second function was for the player to be able to lose all 3 lives if the enemy AI touched the players piece 3 times. 
The third function was 


## 7.0 Evaluation

 
