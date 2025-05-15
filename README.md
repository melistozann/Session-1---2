# Session-1 and 2 
# Poker Hand Simulator

This is a Python project in class  where we simulate drawing poker hands from a deck and check how often we get a pair (or a flush) . It  runs a bunch of hands and calculates the probability.

### What it does:
- Creates a normal 52-card deck
- Deals 5 cards like in poker
- Checks if the hand has a pair or is a flush
- Repeats that thousands of times to get a percentage

### How I did it:
There are 3 main classes:
- `Card`: just a card with a suit and rank
- `Deck`: holds all the cards and shuffles them
- `PokerHand`: where I check if the hand is a pair or flush

Then I run a loop about 10,000 times to see how often a pair comes up.

### Sample output:
