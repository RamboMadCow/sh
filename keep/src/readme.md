-h, --help                        show this help message and exit
            
-s SECONDS, --seconds SECONDS     Define in seconds how long to wait after a user is
                                  considered idle. Default 300.

-p PIXELS, --pixels PIXELS        Set how many pixels the mouse should move. Default 1.

-c, --circular                    Move mouse in a circle. Default move diagonally.

-m MODE, --mode MODE              Available options: keyboard, mouse, both (mouse & keyboard) and scroll. 
                                  Default is mouse. 
                                  This is the action that will be executed when the user is idle. 
                                  If keyboard is selected, the program will press the shift key. 
                                  If mouse is selected, the program will move the mouse. 
                                  If both is selected, the program will do both actions.

-r RANDOM RANDOM, --random RANDOM RANDOM
                                  Usage: two numbers (ex. -r 3 10). Execute actions based on a 
                                  random interval between start and stop seconds. 
                                  Note: Overwrites the seconds argument.
