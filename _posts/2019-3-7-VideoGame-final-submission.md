- - -
layout: post
date: 2019-3-7
name: louis gonzalez's blog
- - -

I have finished my game this week and it is looking really good,it even has 2 dimentional movement,which is right and left movement in the game. A portion of the final product looks like this 

```
; update-player : Number String-> Number
(define (update-player x y  key)
  (cond
    [(string=? key "up")(make-posn x (+ y 15))]
    [(string=? key "down")(make-posn x (- y 15))]
    [(string=? key "left")(make-posn (- x 15)y)]
    [(string=? key "right")(make-posn (+ x 15)y)]
    [else (make-posn x y) ]
   ))
   
```https://www.wescheme.org/view?publicId=qtZbBRNh2U

This is the code for 2 dimentsional movemnt,which needs to use a function we haven't learned about,posns, which either create or take in the current position of the chararcter. The first line is the contract,which contains and shows the different data types used in the function. The next line is the function,which makes a new word in the current game's vocabulary and creates a value for it,which in this case makes update-player the value of the x and y key when they are changed by a key press. The next line is the condition start,which starts new braches until a else branch is created. The next line is the first condition which detects if the correct key is being pressed for it to be activated and then acts out the function it needs to do which in this case is to create upward movement by adding to the current y value,this only occurs when the up arrow key is pressed. The next 4 lines are like this with slight moddifications, the next lines detect either the down,left,or right arrow keys have been pressed,which in turn creates either down,left,or right-ward movement,which is caused by either subtracting from the current y value, or adding/subtracting from the current x value. The next line is the else condition,which is only activate when all the other conditions have not been activated. The final line closes the function with closing parenthesis.The game can be played here.

https://www.wescheme.org/view?publicId=qtZbBRNh2U
