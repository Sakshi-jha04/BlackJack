# BlackJack

Description:

This Python program simulates a simplified version of the classic casino card game, Blackjack (also known as 21). The program utilizes object-oriented programming (OOP) principles to define classes for cards, decks, hands, and the game itself.

Card Class: Represents a single playing card with attributes for its suit and rank. The rank includes both the face value and the actual rank (e.g., "A" for Ace, "K" for King).
Deck Class: Represents a deck of 52 cards, with methods for shuffling the deck and dealing cards.
Hand Class: Represents a player's or dealer's hand of cards. It includes methods for adding cards, calculating the total value of the hand, checking for blackjack, and displaying the hand.
Game Class: Orchestrates the gameplay, allowing players to play multiple rounds of Blackjack. It handles dealing initial cards, player decisions (hit or stand), dealer actions, and determining the winner of each round.
Features:

Gameplay Simulation: 

Players can play multiple rounds of Blackjack against a computerized dealer.
Interactive Interface: Players can choose whether to hit or stand during their turn.
Basic Rules Enforcement: The program enforces basic Blackjack rules, such as busting if a player's hand value exceeds 21 and the dealer's requirement to hit until reaching a hand value of 17 or higher.


Usage:

1. Run the program.
2. Enter the number of Blackjack games you want to play.
3. Follow the prompts to play each round:
4. You'll see your initial hand and the dealer's visible card.
5. Choose to hit (receive another card) or stand (end your turn).
6. Once you've completed your turn, the dealer will play their hand.
7. The winner of the round will be announced, and the game will proceed to the next round.
