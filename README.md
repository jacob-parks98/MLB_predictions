# MLB_predictions

## Summary
 As an avid sports bettor, I have always struggled with predicting the outcomes baseball games. Therefore, I saw a personal need to create a resource that can help me change my luck and become profittable when betting on Major League Baseball games. This model is trained on in-game data from 2012-2021 and has ~64% accuracy, outperforming Casino odds, which have roughly 54% accuracy.

 ## Contents
 This repository contains:
  - **Webscraping**: Webscraping in game data
  - **Odds_cleaning**: Acquiring and cleaning historical betting odds data
  - **modeling**: Building the predictive model
  - **full-model**: Implementing the model for daily picks

 ## Data
 The in-game statistics for over **20,000** games from **2012-2021**  was scraped from 
 baseball-reference.com and includes:
  - Team Batting Statistics (BA, R, AB, etc.)
  - Team Pitching Statistics (IP, ERA, SO, etc.)
  - Individual Pitcher Statistic (IP, ERA, SO, etc.)
 
 The Casino odds were downloaded from sportsbookreviews.com and include the moneyline and results of each game from each game from 2012-2021