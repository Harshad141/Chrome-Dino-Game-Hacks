# Chrome-Dino-Game-Hacks
## Playing 
* Press **_Space-bar/up_** for JUMP. 
* Press **_Down Arrow_** to DUCK to avoid birds that appear after 450 points.
* Press **_Alt_** to pause.
## OPEN CONSOLE (press F12 and click on console).
## Make sure you have no active Internet connection.
## Console is where you can run your code (paste the given code in console and press enter)
### TWEAKING SPEED (will increase and decrease the speed)
* **(Runner.instance_.setSpeed(1000))**
### IMMORTALITY (Dino won't die neither from the Cactus bush nor from the Birdie thing).
All commands are case sensitive
- **(var original = Runner.prototype.gameOver**) (It stores the original game over function in a variable)
- **(Runner.prototype.gameOver = function(){}**) (makeing the game over function empty)
### Control Dino jump
- **(Runner.instance_.tRex.setJumpVelocity(10)**) (change the .setJumpVelocity accordingly it is set 10 as default)
### Set a current score
- **(Runner.instance_.distanceRan = 10000 / Runner.instance_.distanceMeter.config.COEFFICIENT**) (here setting a score of 10000 you can set any score between 0-99999 unless you want chrome to crash, this sets the current score. FYI the current score changes after every restart)
