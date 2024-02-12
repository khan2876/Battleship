# Battleship  

## Overview  
This game is played by guessing spots on an opponent's board to fire at.  After guessing a cell to attack, 
the opponent will tell you if you hit their ship, or missed.  

For this initial project, we'll make a scaled down version of the game.  

## Requirements  
There should be two modes to play.  
Easy should make a 5x5 grid of Cells  
Hard should be 7x7.  

The Battleship should take up 5 cells.  For this 'game' the Battelship should start in the same place every time.  
It should be centered in the middle row.  

The player will have 15 shots to hit all 5 parts of the Battleship.  The game ends when they run out of ammo, or the Battleship is sunk.  

The game should ask for the row and column to be fired at.  It might be easier to ask for these one at a time.  

If the player shoots off the board, tell them they chose an invalid space and to try again.  This should use one of their turns.  
If they shoot at a space that's already revealed, tell them to try again but do not deduct a shot.  

The board should print after each turn.  
The initial easy board could look like this: 
- - - - -  
- - - - -  
- - - - -  
- - - - -  
- - - - -  

After five shots it could look like this:
- O - - -  
- - - -- O  
- X X - -  
- - - O -  
- - - - -  

The 'O' represents shots that missed.  The 'X' represents hits to the Battlesip.  

## Grading  
Logical Structure (3 pts)  
The Board and Cell classes should have attributes, constructors, and methods that make sense.  

UI  (3 pts)
The game should be easy to follow and give approriate feedback.  

Working Game (3 pts)  
The game should behave as specified, track shots taken, print the board properly, and end when it should.  

Regular commits (3 pts)  
Name them well, and do them at logical intervals.  

Formatting (1 pt)
Tabs and whitespace should be appropriate.  Naming of variables should also make sense.  

## Possible improvements  
These are things you could do to improve your game.  None of this is required.  
* Randomize the location of the ship
* Make a two player mode.  Each player can enter where their ship should go, and would take turns making shots.
* Add difficulty levels.  There might be different numbers of shots for each level.
* Option for a random shot.  You can decide if this should go to an unrevealed cell or not.  
