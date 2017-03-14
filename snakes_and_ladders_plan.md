BOARD (class)
    Grid size (attribute)
    Placement of snakes (attribute)
    Size of snakes (attribute)
    Placement of ladders (attribute)
    Size of ladders (attribute)
    Numbers on squares - starting from bottom left working up in a step formation (attribute)
        Move game piece based on dice roll (method)
        Move down if land on snake (method)
        Move up if land on ladder (method)
        Win game if land on last square (method)



PLAYERS (class)
    Name (attribute)
    Colour of game piece (attribute)
    Max number of players (attribute)
        Order of play - players take turns (method)



DICE (class)
    Random number (attribute)
        Roll dice (method)
        If player rolls 6, can roll again (method)
        Have to roll exact number to land on final square (method)