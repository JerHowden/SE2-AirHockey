## Goal of the project

The goal of this project is to build a working air hockey game that will work with single player with AI function, local two player and potentially LAN two player. This will demonstrate a complex but working piece of software made in Java such the group of developers show understanding and ability over the idea of software engineering.


Potential users

	Everyday person who wants to relax by playing games 
	Younger people who want to play a simple game
	Older people want to play due to its simple controls
	People by themselves that are bored
	Pair of people that want to play a game on one computer
	People who are in the same LAN who want to play a game together
	


Use cases

	1: User exits game
This can be done in several different ways one main method will be to force quit in any way be it alt-F4 or hitting the x in the top right. Another method would be to use the escape key. This is so that the user is not trapped in the game and taking up the computer process that the user wants to use for other sources. No data will be saved after exit.

	2: User selects play type
There are several play types available to the user through the menu. The three main types will select between a single local player, two players local, and two players LAN. The Single player will have a simple AI that the user can play against. The two player local would be played using the keyboard where one player will use wasd and the second the arrow keys. Finally the LAN play should be able to connect and exchange information between separate connected computers.
	
	3: User can look at previous scores
 Allow the user to how they fared in previous games. This will not however carry the information over after exiting the game. The information will be listed along with a baseline attempts and show how well the user did compared to tests by the development team. So for example if the user loses by one point then the users will show up on the record screen having lower rank then if they have five points higher than the AI. If it is a Two person game then it would just list the scores.
	
	4: User starts new game
This new game is started by selecting a button on the menu screen. It should automatically start the game type selected. It should immediately go to the game screen but wait for input from the user or indicate the the game will start soon so the user is not surprised. 
	
	5: User checks help for instructions and assorted info
This is an option form the menu that gives information to the user. This information will allow them to know how the different play type options work and why they would select each. It will also have controls on how to play for the different play styles.


Teammate contributions so far
1. Thomas Sievers: Creating the ring and background
2. Jonathan Turner: User Doc, Menu
3. Elias Moreno: Main Menu and differentiating between game state and menu state.
4. Benjamin Kim: mouseListener, paddle, and puck movement
5. Jeremiah Howden: Main Game Engine, Window, FpsTimer, and Graphics
