# Paint-ball-fighting
An academic team project(game) that was conducted with assembly language(DOSBOX).
the game is a 2-player game that is played on two Pcs connected using serial port.
the game is basiclly a shooting game where each player is granted a number of bullets to fire, each time an enemy player is hit by a bullet he losses health, when a player's health  reaches zero he losses the round.
the grid where the players do there game is split evenly between them into two regions, each owned by a player. if a player enters the enemy player's zone he losses the ability to fire bullets.
in each zone there is a stacking area where a player can go in order to reacharge bullets.
there are also boxes that are scattered accross the grid, boxes blocks player movments (i.e a player cannot step on a box) however a box is destroyed when it is hit by three bullets of either players. so a box can block bullets up to three times(i.e it can used by players as shields).
each box containes a powerup or a trap, the powerup/trap appears when the box is destroyed. a powerup might increases the health or reacharge bullets, a trap will decreases the health.
