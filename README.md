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

