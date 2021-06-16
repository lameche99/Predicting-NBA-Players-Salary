# Proposal
# Introduction
The National Basketball Association is known to be one of the most lucrative professional sports in the world. The NBA athlete's salary has increased over the years and the athlete's contracts have been a topic of interest among many sports fans. There is a sea of data available about the NBA player’s ranking, scores, positions, and contracts. The intriguing question is what factors play the most important part in the decision of an NBA player’s salary. Our team has decided to attempt to answer this question through this project.


# Problem Definition
The salary cap and the luxury tax in the NBA will reach $113 and $136 million respectively for the 2021-2022 season. This puts substantial constraints on managers and coaches in trying to build a competitive team within these strict limitation. Thus, a model able to predict appropriate players’ salaries is crucial to the league. 
In this project we will use players’ data and stats from the past 5 seasons - as salaries have dramatically risen compared to earlier years - to find which ones are most correlated to salary and then predict the potential cap hit for the 2021-2022 season. The goal of this project is to provide reasonable recommendations to both players and teams regarding their intrinsic value base on their on-court performance.

# Methods
We will be scraping data from basketball-reference.com which a historical and up to date repository for statistics for the NBA. To constrain the data set, we will only be considering signed, non-rookie contracts over the past 5 years for salary prediction. For cleaning data, we will consider each players average across the following statistics: Points Per Game(PPG), Minutes Played Per Game (MPG), Rebounds Per Game (RPG), Assists Per Game(APG), Blocks (BLK), Steals (STL), Turnovers(TOVR) mapping each to the player’s salary. Our team will be using a linear regression model to identify the stat correlations that are most correlated to salary prediction and use those stats to predict future contract offers. We will then perform analysis using K-Nearest Neighbors to classify the players which are underpaid yet statistically over performing or vice versa.


# Potential Results and Discussion
For this project, we expect to have a machine learning algorithm that is able to predict what an NBA player’s salary should be as a percentage of the overall salary cap. This predictor could be used a way for general managers to find the best way to optimize their team with respect to getting the most talent, skill, and highest chance to win with the least amount of money spent. In a league like the NBA where there is a salary cap, it is very important to be efficient with the salaries so that you have more resources on the court than your opponent.
