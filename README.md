# snake-and-ladder-using-java

Machine Coding

PROBLEM STATEMENT

Create a snake and ladder application. The application should take as input from the command line.

Number of snakes (s) followed by s lines each containing 2 numbers denoting the head and tail positions of the snake.

Number of ladders (l) followed by l lines each containing 2 numbers denoting the start and end positions of the ladder.

Number of players (p) followed by p lines each containing a name.
After taking these inputs, you should print all the moves in the form of the current player name followed by a random number between 1 to 6*NoOfDices denoting the die roll and the initial and final position based on the move.

Format: <player_name> rolled a <dice_value> and moved from <initial_position> to <final_position>

When someone wins the game, print that the player won the game.

Format: <player_name> congrats you won the game.

Rules of the game

The board will have 100 cells numbered from 1 to 100.

The game will have a six sided dice numbered from 1 to 6 and will always give a random number on rolling it.

Each player has a piece which is initially kept outside the board (i.e., at position 0).

when each player gets his turn he will roll a dice which gives a random number from 1 to 6 and based on the number he will move to the next_position.

In between the cells there are snakes and ladders.

Snake will have a head and tail and head is always have greater value than tail.

Ladder will have a start and end position and start position will have low value than end.

Whenever a player ends up at a position with the head of the snake, the player should go down to the position of the tail of that snake.

Whenever a player ends up at a position with the start of the ladder, the player should go up to the position of the end of that ladder.

Optional Requirements

The game is played with two dice instead of 1 and so the total dice value could be between 2 to 12 in a single move.

The board size can be customizable and can be taken as input before other input (snakes, ladders, players).

On getting a 6, you get another turn and on getting 3 consecutive 6s, all the three of those get cancelled.
