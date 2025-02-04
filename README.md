
Bowling Challenge
=================

Count and sum the scores of a bowling game for one player (in JavaScript).

- Score starts at 0 
- There are 10 frames in a game
- There are 2 rolls per frame
- If the player knocks down all 10 pins on the first roll its a strike and that frame ends
    - Bonus points for strike are the points from next 2 rolls
- If the player knocks down all 10 pins in 2 rolls its a Spare
    - Bonus points are points from next roll
- If the player rolls a strike or spare in the 10th frame they can roll the additional balls for the bonus. 
    - They can never roll more than 3 balls in the 10th frame. The additional rolls only count for the bonus not for the    regular frame count. 
- If a player never scores it’s called a gutter game 
- If a player plays 12 strikes its called a perfect game - score is 300


## Bowling — how does it work?

### Strikes

The player has a strike if he knocks down all 10 pins with the first roll in a frame. The frame ends immediately (since there are no pins left for a second roll). The bonus for that frame is the number of pins knocked down by the next two rolls. That would be the next frame, unless the player rolls another strike.

### Spares

The player has a spare if the knocks down all 10 pins with the two rolls of a frame. The bonus for that frame is the number of pins knocked down by the next roll (first roll of next frame).

### 10th frame

If the player rolls a strike or spare in the 10th frame they can roll the additional balls for the bonus. But they can never roll more than 3 balls in the 10th frame. The additional rolls only count for the bonus not for the regular frame count.

    10, 10, 10 in the 10th frame gives 30 points (10 points for the regular first strike and 20 points for the bonus).
    1, 9, 10 in the 10th frame gives 20 points (10 points for the regular spare and 10 points for the bonus).

### Gutter Game

A Gutter Game is when the player never hits a pin (20 zero scores).

### Perfect Game

A Perfect Game is when the player rolls 12 strikes (10 regular strikes and 2 strikes for the bonus in the 10th frame). The Perfect Game scores 300 points.

