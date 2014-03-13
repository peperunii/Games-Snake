This is a small console game "Snake" written on C.
Compiled succesfully using Windows 7 / Visual Studio 2013

About this game:
 - Do not touch the wall.
 - Use arrows to change direction
 - Eat food to increase the score.
 - Food will dissapear after some time and re-appear on a different place.

Controls:
 - arrows. 

Config file:
 - should be in the same folder as project with name "config.cfg"
 - it contains:
arraySizeX					16 //
arraySizeY					16 // game window dimensions - smaller is better
StartingDirection				3  // 1 = right, 2 = up, 3 = left, 4 = down, 0 = random
snakeSize					5  // 3 - 30
IncreaseSpeedOnEveryFood			1  // 0 or 1
- The numbers above are recommended. The values in config file should be correct. Put the above lines in config.cfg file (without comments)
