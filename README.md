# ST-language
Commands:
Var: to use var type VAR then name then = num example: VAR f = 20
Rectangles: currently, all you can make is a rectangle and to make it here is the setup: RECT [name] [x] [y] [width] [height] [R] [G] [B] obviously, remove brackets
Move: to move a rectangle you do MOVE [name] [dx] [dy] also remove brackets and replace name with whatever you called the rectangle
Color/colour: to change color/colour you do COLOR [name] [R] [G] [B] remove brackets and replace name with whatever you called the rectangle and change r,g and b to values of red green blue
Functions: to define a function do FUNCTION [name] [commands] remove brackets and change name to function name and commands to the commands you want your function to do and to call it,simply write the function name
Keypress: To detect a key being pressed type KEYPRESS [key] [action] without brackets and say you wanted to make e move right with a function you would do KEYPRESS e moveRight
Comments: to add a comment, or an undetected bit of writing do // then whatever you want
Putting it together: below is an example script
VAR x = 100 // creates variables for x and y of square
VAR y = 100
RECT myRect x y 50 50 255 0 0  // makes a red rectangle called myrect

FUNCTION moveRight MOVE myRect 10 0  // defines/makes the moveright function

moveRight  // calls the moveright function

BGCOLOR: to change the background color you can do BGCOLOR R G B 
Loop: to  make a loop you can do LOOP (num) (command) remove brackets there is also LOOP FOREVER(example below)
BGCOLOR 0 255 0
RECT square 190 190 20 20 0 0 255
LOOP FOREVER
    MOVE square 2 0
    WAIT 2
END

Wait: to wait you do WAIT (number of secs) remove brackets

useful tips:
190 190 is the center
