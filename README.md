# Tic Tac Toe Project
Tic-tac-toe is a paper-and-pencil game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds 
in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

##Features
  Two Player

## Installation
 
 #Rules
##In random order

a game is over when all fields are taken
a game has nine fields in a 3x3 grid
a player can take a field if not already taken
there are two players in the game (X and O)
players take turns taking fields until the game is over
a game is over when all fields in a column are taken by a player
a game is over when all fields in a row are taken by a player
a game is over when all fields in a diagonal are taken by a player

Instructions
How to run the tests
From the main root you can use gradle to execute the tests, running

gradle clean test
How to build an executable jar file
From the main root run

gradle clean
gradle buildJarWithDependencies
Launch the jar application
Go to the folder

/build/libs

and run

java -jar tic-tac-toe-kata-all.jar
How to play the game
Two human players can play the game.

Each player writes the coordinates of the field he wants to take, for example A1.

Player X starts.

The game ends when either three consecutive fields have been taken by a player, or when all the fields have been taken.

