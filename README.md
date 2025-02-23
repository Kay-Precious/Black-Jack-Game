# Black-Jack-Game

A simple implementation of the popular casino game Blackjack, also known as 21. The game allows a user to play against the computer.

Requirements

- Python 3.x
- random library

Installation

1. Clone the repository using git clone
2. Run the game using python blackjack.py

Gameplay

1. The game starts with the user and computer being dealt two cards each.
2. The user can see both of their own cards and one of the computer's cards.
3. The user can choose to either 'hit' to receive another card or 'pass' to stop receiving cards.
4. If the user's score exceeds 21, they immediately lose the game.
5. After the user has finished their turn, the computer's score is revealed and the computer draws cards until they have a score of 17 or higher.
6. The winner of the game is determined by comparing the user's and computer's scores.

Code Structure

The code is structured into the following functions:

- deal_card(): Returns a random card from the deck
- calculate_score(cards): Calculates the score of a given hand of cards
- compare(u_score, c_score): Compares the user's and computer's scores to determine the winner
- play_game(): Controls the flow of the game

