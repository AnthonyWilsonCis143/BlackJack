# BlackJack Project
Creating a blackjack clone using object orientation in Java.

## Required Classes

### Card Class
1. Attribute: Suit
2. Attribute: Value
3. Method: toString()
4. Getters and setters for all attributes

### Deck class
1. Attribute: deck
    * List of card objects
2. Attribute: CardCount
    * Integer Card Count
3. Attribute: Suits
    * List of suits (String list)
4. Attribute: Cards
    * List of face cards (String list)
5. Method: GenerateDeck()
    * Throw all the cards into a list (With face cards and suits)
6. Method: Shuffle()
    * Shuffles the cards and puts them in random slots of the list
7. Method: DrawRandomCard()
    * Pick a random card from the deck. Returns a random card object
8. Getters and setters for all attributes

### Player class
1. Attribute: Name
    * name of the player
2. Attribute Score
    * Current score of the player
3. Attribute: Money
    * How much money the player has
4. Attribute: Cards
    * Current cards the player has

5. Attribute: TotalCardValue
    * Total card value of the player (Sum of all cards)

6. Getters and setters for all attributes

7. Method: GetCardTotal()
    * adds all the cards up and returns the total -> int

8. Method: GetCards()
    * Gets list of current cards
9. Method: AddCard()
    * Adds card to the players cards list

### GameRoom Class
1. Attribute: Players
    * List of player objects
2. Attribute: MaxPlayers
    * Maximum number of players that can be in the game at one time
3.  Attribute: Deck
    * Current deck object for the game room.

4. Attribute: Buy in
    * current buy in for the game room. (Max purchase)

5. Getters and setters for all attributes

6. Method: AddPlayer()
    * Adds player to the game room, Checks how many players are in the game

7. Method: PlayerCount()
    * Gets how many current players in the game

8. Method: RemovePlayer
    * removes player from the room

9. Method: DealCards()
    * Deal cards to all the players in the room

10. Method: GameCycle()
    * Infinite loop till a winner is determined, or everyone busts.
