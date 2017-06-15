#SorryBoardGame
SET UP:
Enter everyones name and assign them a specific color (Blue, Red, Green or Yellow)
Figure out who will go first (Random number Generator)
player blue = p1
player yellow = p2
player green = p3
player red = p4
Make a gameBoard // Create a method for this
There are 11 different playing cards this game (create a random generator for each card and assign what each one does)


What each card does:
1: You can move a pawn from the start or move forward 1 space.
2: You can move a pawn from the start or move forward 2 spaces. You must draw again.
3: Move forward 3 spaces.
4: Move backward 4 spaces.
5: Move forward 5 spaces.
7: Move forward 7 spaces or split between 2 pawns (e.g. 3 spaces for one pawn, 4 spaces for another).
8: Move forward 8 spaces.
10: Move forward 10 spaces or move backward 1 space.
11: Move forward 11 spaces or switch places with an opponent. If it is impossible to move forward 11 spaces, and there are no opponent pawns on the board, then you will have to switch places with your partner or forfeit your turn.
12: Move forward 12 spaces.
Sorry!: You can save the card for later use, or you can use it to bump an opponent's pawn to the start.

GAME RULES:
1. Draw a card at the beginning of each turn - You must draw a 1 or 2 to start the game

2. Jump over pawns that belong to you or other players -  If you draw a card that will advance one or more of your pawns past another player’s pawns or past your own pawns, then you can jump over them

3. Bump your opponenents pawns if you land on an occupied space - If you land on the same block as your opponents, they will have to go back to start and restart

4. Slide if you land on a SLIDE triangle -  If you land on a SLIDE triangle that is not the same color as the pawns you have chosen, then you get to slide to the circle at the end of the triangle

5. Get all of your pawns to the HOME space to win the game - To win Sorry, you need to get all of your pawns to the home space

Instead of creating one whole program, create seperate classes for something specific (board, card, pawn and player) and have a main program

For board: Print out the actaul boards
For card: Have two methods, one for setting up the cards and another for drawing a card - random number generator
For pawn: Have a method to initialize the path for each player, a method for the movement of each card, method to check if each pawn reached home (how they win) and a method to slide
For player: Have a method to check how many of the pawns of the player have reached home, method to play the game ( tell what each card is suppose to do) and a method to return the location of all the pawns in the Player object








