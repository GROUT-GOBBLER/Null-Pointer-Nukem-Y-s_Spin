# Null-Pointer-Nukem-Y-s_Spin
Win-condition: get to 1,000,000 points.
Lose-condition: If your knowledge score goes below 1/4 of your max score from the current game, you lose.

Professor tokens (execute given action in exchange for 10 brownie points):
 - The Ole' German professor: destroys all enemy tokens.
 - The English Educator: gives 10 seconds of invincibility.
 - The American Academic: doubles knowledge points.
 > If you collide with a professor token with <10 brownie points, you will lose all of your brownie points but the action will not be performed.

Enemy tokens (execute negative debuff):
 - Bug swarm: every 1 second, lose 10% of current knowledge score. Remove debuff by colliding with professor token (don't need 10 brownies to remove debuff).
 - Null pointer: lose either 10% of current knowledge score or 10 knowledge points (whichever is greater).
 - Procrastination pirate: freeze player for 3 seconds.

Points tokens:
 - Coding cookbook: +1 knowledge score.
 - PhD pendant: +25 knowledge score.
 - Brownie point: +1 brownie point.

General rules:
 - If the player goes 60 seconds without colliding with any enemy tokens, player enters "spectar mode".
 - Spectar Mode: double points tokens spawns, double professor tokens, all points tokens give double knowledge score, infinite brownie points, and player invincibility for 10 seconds.
