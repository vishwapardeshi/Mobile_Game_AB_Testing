# Mobile Game A/B Testing

Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. 

## Business Problem

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

> Where should the gates be placed to maximize player retention? 

## Result of A/B Test
**The bootstrap analysis** result tells us that **there is strong evidence that 7-day retention is higher when the gate is at level 30 than when it is at level 40.** The conclusion is: If we want to keep retention high — both 1-day and 7-day retention — we should not move the gate from level 30 to level 40. There are, of course, other metrics we could look at, like the number of game rounds played or how much in-game purchases are made by the two AB-groups. But retention is one of the most important metrics. 

## Tools
1. Python, Pandas, Matplotlib
2. Jupyter Notebook



