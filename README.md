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

  ### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* A/B Testing

### A/B Testing Steps

* Understand the business problem and data
* Detect and resolve problems in the data. Check for missing values, outliers, and unexpected values.
* Look at summary statistics and plots. This will help you understand the distribution of your data and identify any potential problems.
* Apply hypothesis testing and check assumptions. Make sure that your data meets the assumptions of the statistical test you plan to use.
* Apply tests (Shapiro, Levene Test, T-Test, Welch Test, Mann Whitney U Test). Choose the appropriate statistical test to compare the two groups.
* Evaluate the results. Calculate the p-value and interpret the results of the statistical test.
* Make inferences. What can you conclude about the impact of the change you tested?

### Technologies
* Python

### Librariess Used
* Matplotlib
* Numpy
* Pandas
* Scipy
* Seaborn

### Results
In this project, we analyzed an A/B test to see how moving the first gate in Cookie Cats from level 30 to level 40 would affect player retention and game rounds. We first checked the data for missing values and outliers. Then, we used summary statistics and plots to understand the data and the problem.

Before running the A/B test, we shared some details about the game, players, problems, and suggestions. After running the test, we analyzed the results and found that the data was not normally distributed. Therefore, we used the Mann-Whitney U test, a non-parametric test, to compare the two groups.

The Mann-Whitney U test showed that the two groups were not similar, meaning that there is a statistically significant difference between the two groups in terms of game rounds. In other words, moving the first gate from level 30 to level 40 had a statistically significant negative impact on game rounds.


* Which level has more advantages in terms of player retention?
Having the first gate in Cookie Cats at level 30 is better for player retention than having it at level 40. This is because players are more likely to keep playing and come back to the game if they can play for longer before hitting the first gate.

There are a few possible explanations for this. One possibility is that players are more likely to get hooked on the game if they can play for a longer period of time before they have to wait. Another possibility is that players are more likely to come back and play the game if they know that they are making progress towards the next gate.

In other words, players are more likely to stick with the game if they don't have to wait too long to progress.
