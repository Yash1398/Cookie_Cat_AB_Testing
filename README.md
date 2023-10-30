# Cookie_Cat_AB_Testing


### Intro
Cookie Cats is a popular mobile puzzle game where players connect tiles of the same color to clear the board and win the level. The game features gates that force players to wait before they can progress or make an in-app purchase.
This project analyzes the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. The goal of the test was to measure the impact on player retention and game rounds.

### Data
The data is from 90,189 players that installed the game while the A/B test was running. The variables are:
* userid: a unique number that identifies each player.
* version: whether the player was put in the control group (gate_30 - a gate at level 30) or the test group (gate_40 - a gate at level 40).
* sum_gamerounds: the number of game rounds played by the player during the first week after installation.
* retention_1: did the player come back and play 1 day after installing?
* retention_7: did the player come back and play 7 days after installing?
