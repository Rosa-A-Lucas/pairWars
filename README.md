# pairWars

The program contains three players, one dealer, one deck containing 52 cards that need to be randomized (shuffle),The program is broken down into different functions, each function has a specific task to perform. Down below are some of the functions used in the program and the functionality. . Down below are some of the functions used in the program and their functionality.

void setDeck(Deck*& d) This function initializes the deck first, then shuffles it.

void shuffleDeck(Deck*& d, const int times) This function shuffles the deck by swapping the cards using the RNG seed.

void dealRound(Player* player[], const int player_count) This function distributes cards to the players.

void printStatus(const Player* const player[], const int num_players) This function lists what cards each player has.

void printDeck(const Deck* d, const int print_option) This function prints the current cards in the deck.

void printHand(const Player* p, const int print_option) { This function prints the current cards in each player’s hands.

void drawCards(Player*& p, Deck*& d) This function distributes cards from the deck to players.

void cardDiscard(Player*& p, Deck*& d) This function allows players to remove a card from their hand and place it back into the deck.

void placeInDeck(Deck*& d, const int card) This helper function handles the card being placed back into the deck.

int takeFromDeck() This helper function handles the cards being taken from the deck.

void* playerTurn(void* player) This function handles the overall gameplay. Players draw cards and it checks for a win.

void concludeRound(Player*& p) This function ends the round and clears each players’ cards in hand.

void WriteInLog(std::string l) This function handles the log. All events are recorded here.
