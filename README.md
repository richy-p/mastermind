# mastermind
Mastermind game simulator to check algorithm

Notes:

Color code of length 4 made from selecting from 6 possible colors, duplicates are allowed.

## Color list to choose from
initialSet = set(['Green','White','Pink','Yellow','Purple','Orange'])

## Parts that are needed

1. Generate the passcode
    > Randomly select 4  colors with replacement

2. Algorithm to generate guesses
    > Start by selecting one random color - use for all 4 positions


3. Guess checker 
    > checks guess and returns the number of positions guesed correctle and the number of correct colors but incorrect positions
