# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
The most difficult part of tic-tac-toe was making the has_won function. It involved a lot more code than every other function as it required every possible combination to win. The diagonal wins were more pesky since the numbers on the board didn't follow a similar pattern to each other.

2. Explain how you would add a computer player to the game.
I would probably use a randomizer to pick the spots for the computer. It wouldn't lead to the best move but it allows for a computer to play. It would not matter if the randomizer chooses a spot where something has already been placed as it is an invalid move and would allow the computer to continue until it finds a vacant spot.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
The best moves would probably first include trying to make the computer stop potential wins by the other player and if it doesn't spot any potential wins then it could place its move on a tile where it can make win on the next turn. This is probably the human way of thinking for tic tac toe, its not complete offense. Coding wise, it would be quite troublesome.