# TAKI

This simple project utilizes Jupyter-based interactions to implement a basic TAKI game.

Taki is a card game developed by Israeli game inventor Haim Shafir in 1983.
Each player follows the preceding card, laid on the table, with a card of the same color or figure. Special cards may change the direction of play, skip a player's turn, make other players draw cards, change the color and allow a player to discard more than one card. 
The object of the game is to discard all the cards in your hand.

The code is implemented with the following classes:
<p>
<code>Card</code> - implements a single game card, with functioanlities such as print and value getters.<br>
<code>CardStack</code>   - implements a list of Card objects, with functionalities such as add, remove, shuffle, 
               initialize as empty or full.<br>
<code>Player</code>      - implements a game player. A Player has a hand (CardStack object), and can be either  
               a human or a computer. <br>
               the class offers several functionalities such as add and remove cards, input interface  
               for the human user, and play functions that allow a human to play, and define the   
               strategy of the computer.<br>
<code>GameManager</code> - implements the game management. It initializes the Player objects, the deck of cards 
               (CardStack), the table (CardStack). It's main functionalities are validation of the game rules, and the proper run cycles of the game.<br>
