# Classic Arcade Game Clone Project

## OVERVIEW

**Basic Functionality**

In this game you have a Player and Enemies (bugs). The goal of the player is to reach the water, without colliding into any one of the enemies.

The player can move left, right, up and down.

The enemies move at varying speeds on the paved block portion of the game board.

Once a the player collides with an enemy, the game is reset and the player moves back to the starting square.

Once the player reaches the water (i.e., the top of the game board), the game is won.


**Instructions**

- Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking my submission.

- Make sure the functions I write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within my class and class prototype functions to refer to the object the function is called upon.



## DEVELOPMENT STRATEGY

**Issues to address**

Inside the app.js file, I need to implement the Player and the Enemy classes, using Object-Oriented JavaScript. 
Specifically, I need to complete the following:

- The Enemy function, which initiates the Enemy by:
    Loading the image by setting this.sprite to the appropriate image in the image folder, setting the Enemy initial location and setting the Enemy speed.

- The update method for the Enemy.Updates the Enemy location.Handles collision with the Player. 

- I also need to implement the Player class. At minimum I should implement the following:

   The Player function, which initiates the Player by:
 
     -Loading the image by setting this.sprite to the appropriate image in the image folder.

     -Setting the Player's initial location.

* The update method for the Player.

* The render method for the Player.

* The handleInput method, which should receive user input, allowedKeys (the key which was pressed) and move the player according to that input. In particular:

     - Left key should move the player to the left, right key to the right, up should move the player up and down should move the player down.

* Recall that the player cannot move off screen (so I need to check for that and handle appropriately).

* If the player reaches the water the game should be reset by moving the player back to the initial location.

* Once I have completed implementing the Player and Enemy, I should instantiate them by:

   - Creating a new Player object.

    - Creating several new Enemies objects and placing them in an array called allEnemies.

## TECHNOLOGIES USED

Object-oriented Javascript

## Future Improvements

Some additional features I could implement:

- Player selection: allow the user to select the image for the player character before starting the game. I can use the different character images provided in the images folder.

- Score: implement a score for the game. For example, the score can increase each time the player reaches the water, and it can be reset to 0 when collision occurs (or it can be reduced).

- Collectibles:  add gems to the game, allowing the player to collect them to make the game more interesting.

                                              ***
  ### Project Implementation
  
_This project was created by **Aikaterini Alvizou** for the Google Udacity Nanodegree FEND._
