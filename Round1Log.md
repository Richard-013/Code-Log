# #100DaysOfCode Log - Round 1 - Richard Horton

The log of my first #100DaysOfCode challenge.

**Start Date**: 14th February 2025

**Target End Date**: 4th July 2025

**Actual End Date**: 

**Coding Days**:
- [x] Monday
- [ ] Tuesday
- [x] Wednesday
- [ ] Thursday
- [x] Friday
- [x] Saturday
- [x] Sunday

## Log

### Day 1 - Friday - 14/02

- Started work on Crazy Eights card game Unity project
- Made a rough plan of the requirements for the basic game functionality (ignored UI/Animation etc. for now)
- Implemented the Card class to hold individual card data and a Deck class that generates the instances for the cards
- Added an altered Fisher-Yates shuffle as a shuffle function for the deck

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)

### Day 2 - Saturday - 15/02

- Started work on game management class and player class
- Reworked some of the initial code to better suit the use of a game manager entity

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)

### Day 3 - Sunday - 16/02

- Overhauled system to use GameObjects to store all data
- Created functions for distributing hands of cards
- Automatically create cards in scene and position them in each players hand.
- Generated a material for each card from textures and assign them to the correct cards when the deck is generated

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)

### Day 4 - Monday - 17/02

- Reworked card positioning system so initial hand can be any size and overlap cards when needed
- Set deck beside the last played card in center of all players
- Fixed textures for cards by making them opaque but still use Alpha Clipping to tidy corners
- Started functionality of drawing a card from the deck to a player hand

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)

### Day 5 - Wednesday - 19/02

- Overhaul of how cards move to use coroutines and self-calculated smooth movement and rotation
- Updates to functions that move cards to use the new coroutine-based smooth movement system
- Added ability to hide face of card from player with in-script material changing
- Spent a long time debugging and experimenting with coroutines before realising test code was the issue and not material change code

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)

### Day 6 - Thursday - 20/02 (BONUS DAY)

- Cleaned up functions for moving cards in the player's hand
- Added another overload for smooth movement coroutine to allow movement without rotation
- Added ability to draw a card from the deck to a player's hand
- All cards move over to accomodate the new card when it's drawn to the hand
- Added test code with key press inputs to test card draw functionality

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)

### Day 7 - Friday - 21/02

- Added ability to sort the player's hand of cards by face value or suit and face value
- Simplified sorting by creating a separate Insertion Sort function
- Made suits retain their order in hand when sorting by value
- Fixed rotation of cards so that cards only rotate if they aren't already facing the relevant player
- Updated the order of card suits for easier to read hands (Suits now alternate between black and red cards)

Repo for Project: [Crazy Eights](https://github.com/Richard-013/Crazy-Eights)
