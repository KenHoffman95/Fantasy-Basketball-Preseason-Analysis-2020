# Fantasy-Basketball-Preseason-Analysis-2020

# Introduction
In anticipation for the 2020-2021 Fantasy Basketball season, I decided to evaluate each NBA player in order to build a ranking of the players by their fantasy basketball value. I used the 11 statistics (FG%, FT%, 3PM, REB, AST, BLK, STL, TOV, PTS, Double-Doubles, Tripe-Doubles)  that are most commonly used as fantasy basketbal categories in order to build the player rankings. 

# Objective
Perform analysis of NBA player statistics from the 2019-2020 season in order to build a ranking of NBA players by their 2020-2021 fantasy basketball value.

# Dataset
In order to analyze each NBA player's statistics from the 2019-2020 season, I pulled the data from https://www.basketball-reference.com/. The original dataset contains 528 players; all having played minutes in the NBA during the 2019-2020 season. I then removed the players that didn't play meaningful minutes and ended up with a datset of 502 players.

# Process & Repository Contents

* ***Dataset:*** data from https://www.basketball-reference.com/
  * [2019-2020 NBA Stats.xlsx](https://github.com/KenHoffman95/Fantasy-Basketball-Preseason-Analysis-2020/blob/main/2019-2020%20NBA%20Stats.xlsx)
* ***Data Cleaning, Feature Engineering and EDA:*** cleaning data, engineering new features and performing exploratory data analysis
  * [Data Cleaning, Feature Engineering and EDA Pt. 1.ipynb](https://github.com/KenHoffman95/Fantasy-Basketball-Preseason-Analysis-2020/blob/main/Data%20Cleaning%2C%20Feature%20Engineering%20and%20EDA%20Pt.%201.ipynb) (Complete Dataset)
  * [Data Cleaning, Feature Engineering and EDA Pt. 2.ipynb](https://github.com/KenHoffman95/Fantasy-Basketball-Preseason-Analysis-2020/blob/main/Data%20Cleaning%2C%20Feature%20Engineering%20and%20EDA%20Pt.%202.ipynb) (Top 263 Players)

# Findings
Through my analysis, I was able to build a metric that measures each NBA player's fantasy value. The metric assigns a value (0, 1, 2, 3) to each statistical category for a player based on how well they performed in that category compared to the rest of the league. For example, if a player's output in a statistic is in the top 25% of all players, that player receives a 3 for that statistic, whereas, if a players output in a statistic is in the top 50% of all players, but not in the top 25%, that same player would receive a 2. Once a player is assigned a value from 0 to 3 for each statistic, the player's values are then summed to create the Overall Fantasy Value Metric. My analysis yielded the following results:

## Top 10 Point Guards:
1. Kyrie Irving
2. Kyle Lowry
3. Russell Westbrook
4. Damian Lillard
5. Luka Doncic
6. Ben Simmons
7. Jrue Holiday
8. Trae Young
9. Chris Paul
10. Steph Curry

## Top 10 Shooting Guards:
1. James Harden
2. Bradley Beal
3. Zach Lavine
4. Shai Gilgeous-Alexander
5. Devin Booker
6. Marcus Smart
7. Jaylen Brown
8. CJ McCollum
9. DeMar DeRozan
10. Fred VanVleet

## Top 10 Small Forwards:
1. Kawhi Leonard
2. Lebron James
3. Jimmy Butler
4. Will Barton
5. Tobias Harris
6. Paul George
7. Gordon Hayward
8. Kelly Oubre
9. Khris Middleton
10. Jae Crowder

## Top 10 Power Forwards:
1. Giannis Antetokounmpo
2. Anthony Davis
3. LaMarcus Aldridge
4. Jayson Tatum
5. Pascal Siakam
6. Nemanja Bjelica
7. Bam Adebayo
8. John Collins
9. Brandon Ingram
10. Domantas Sabonis

## Top 10 Centers
1. Joel Embiid
2. Nikola Jokic
3. Karl-Anthony Towns
4. Nikola Vucevic
5. Kristaps Porzingis
6. Jusuf Nurkic
7. Deandre Ayton
8. Andre Drummond
9. Jonas Valanciunas
10. Thomas Bryant


