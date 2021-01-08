A standard deck of playing cards contains 52 cards. Each card has one of four suits
along with a value. The suits are normally spades, hearts, diamonds and clubs while
the values are 2 through 10, Jack, Queen, King and Ace.
Each playing card can be represented using two characters. The first character is
the value of the card, with the values 2 through 9 being represented directly. The
characters “T”, “J”, “Q”, “K” and “A” are used to represent the values 10, Jack,
Queen, King and Ace respectively. The second character is used to represent the suit
of the card. It is normally a lowercase letter: “s” for spades, “h” for hearts, “d” for
diamonds and “c” for clubs.

The function named createDeck will use loops to create a
complete deck of cards by storing the two-character abbreviations for all 52 cards
into a list. Return the list of cards as the function’s only result. The function will
not take any parameters.

The second function named shuffle randomizes the order of the cards
in a list. One technique that can be used to shuffle the cards was to visit each element
in the list and swap it with another random element in the list. I didn't use Python’s built-in shuffle
function.

I used both of the functions described in the previous paragraphs to create a main
program that displays a deck of cards before and after it has been shuffled. The
main program only runs when functions have not been imported into another file
