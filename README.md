# HiLo-Game
Hi Lo game:

Rules:

The user will check if the card number is higher or lower than the next card.
If the player wins, they gain 100 points. If not, they lose 75 points.
The score will start with 300 points.
If the player has no more point or chooses to end the game, the game is over.

About the code:
Two classes:
- The first class "Initial_card" will just get us randomnly the initial Card Number, and the method
show() will display the actual Card Number. 
- The second class "Card" will behave mainly to check the user's guess if they are correct or not.

The code show first the inital card number, then whenever the user wants to play again, a loop is 
repeated to check the user's answer and assign the next card as the actual card for the next game.

The game will be over if either the score will reach 0 or the user ends the game
