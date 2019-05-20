Displays current time using keyboard LED's (Num, Caps, Scroll lock)

Structure:
6 bits for hours in 24-hr format
6 bits for minutes
blank pause for 3 seconds


e.g.

Num   Caps  Scroll
32/4  16/2   8/1   
 ⭕     ⬤     ⭕    16...
 ⭕     ⬤     ⬤    +2 +1 = 19 hours
 ⬤     ⭕     ⬤    32 + 8...
 ⭕     ⭕     ⬤    +1 = 41 minutes
 ⭕     ⭕     ⭕   
 ⭕     ⭕     ⭕    [pause]
 ⭕     ⭕     ⭕   
