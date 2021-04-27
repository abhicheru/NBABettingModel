# NBABettingModel
This is a Model that simulates spreads and over/unders for NBA games in the 2020-2021 season.

Here is a breakdown of each file
-BettingModelRecords.csv : This is a CSV file with data on wins, losses, and pushes for the spread and over/under starting from 4/18/21
-NBABettingModel.ipynb : This is the algorithm for the model that simulates games using the four factors for the spread and a bagging classifier paired with a random forest classifier for the over/under
-nba_stats_2020_2021.csv : This is a CSV file with data for all of the NBA teams
-nba_stats_collector.ipynb : This is a script that scrapes data and writes it into nba_stats_2020_2021.csv using Selenium
-player_stats_2020_2021.csv : This is a CSV file containing statistics for each individual player 
