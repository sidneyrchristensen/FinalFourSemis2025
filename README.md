# FinalFourSemis2025

Predicted how many points the University of Florida would score on Auburn during the final four semi-finals!

Just for fun, I decided to predict how many points Florida would score on Auburn during the Final Four Semi-Finals using a ridge regression model. I did this by taking the opponent stats during all 37 games UF played prior to this game. The opponent stats of each game used are:

FGA (Field Goals Attempted): The total number of field goal attempts made by a player during a game.

FGM (Field Goals Made): The total number of field goals successfully made by a player.

PCT (Field Goal Percentage): The percentage of successful field goals made out of total attempts, calculated as (FGM/FGA) * 100.

3FGA (Three-Point Field Goals Attempted): The total number of three-point attempts made by a player.

3FGM (Three-Point Field Goals Made): The total number of three-point shots successfully made by a player.

3PCT (Three-Point Percentage): The percentage of successful three-point shots made out of total attempts, calculated as (3FGM/3FGA) * 100.

FTM (Free Throws Made): The total number of free throws successfully made by a player.

FTA (Free Throws Attempted): The total number of free throw attempts made by a player.

FTPCT (Free Throw Percentage): The percentage of successful free throws made out of total attempts, calculated as (FTM/FTA) * 100.

OFF (Offensive Rebounds): The total number of rebounds a player collects on the offensive end of the court.

DEF (Defensive Rebounds): The total number of rebounds a player collects on the defensive end of the court.

TOT (Total Rebounds): The total number of rebounds a player collects, both offensive and defensive (OFF + DEF).

AVG (Average): The average number of rebounds per game

PF (Personal Fouls): The total number of personal fouls committed by a player.

AST (Assists): The total number of assists made by a player, i.e., the number of times a player passes the ball to a teammate who then scores.

TO (Turnovers): The total number of times a player loses possession of the ball to the opposing team.

BLK (Blocks): The total number of shots a player blocks from the opposing team.

STL (Steals): The total number of times a player takes the ball away from an opposing player.

PTS (Points): The total number of points scored by a player, including field goals, three-pointers, and free throws.

AVG(1): The points per game of that team

The average values Auburn had for each of these stats were plugged into the model to predict how many points Florida would score given Auburn as its opponent!
The model was only one point off as it predicted 78 points for Florida while the actual number of points Florida scored was 79!
