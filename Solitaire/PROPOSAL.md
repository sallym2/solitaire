# Project Proposal
My project proposal is a Solitaire game.
I would find a card image library to use so I wouldn't have to create them myself and/or using th CImg library.
Also I would need to create or find a way to randomly shuffle the deck. I found a random shuffle example on 
http://www.cplusplus.com/reference/algorithm/random_shuffle/ and there is also the Fisher-Yates shuffle 
https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle
In my project I want to be able to be able to play a game of solitaire by clicking and dragging cards onto each other or
perhaps clicking the card I want to move and then where I want it to go.

The rules I will be following for my game are from https://www.bicyclecards.com/how-to-play/solitaire/.

Before the card can be placed I would have to validate that it was a legal move.
I would set limits as to what cards can go on top: it has to be one count lower and of the opposite color. 
For the foundation piles the card on top would have to be one count higher and of the same suit.
Kings would be the only ones able to be placed in empty spaces on the table.

Unlike the foundation or waste pile when placing a card on top of another card on the table I need to shift it down a bit
so I can see the card under it. 

When I take a card from the waste pile I need the new card shown to be the previous card from the waste pile, not just a
random card in the pile.
Once I go through the stock/hand pile I need to be able to recycle the waste pile and keep it in the same order.

I need a new game button always present on the screen, not just when someone wins the game, in case the game is unsolvable.

Once all the cards are in the correct foundation piles I would declare a winner.


openframeoworks
clickable cards
start solitaire framework

better libraries
ofxNetwork library openframework
have 2 players play the same deck and see who wins fastest
