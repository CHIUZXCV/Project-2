### Project 2

## Background

Our motivation was to predict the results of the English premier league (EPL) fixtures with machine learning to guide a potential betting model.
A machine learning model was used in an attempt to accurately predict the winner of a match.
The core idea was to create a model that would predict the winner of any given match at a higher success rate than betting odds-makers were currently achieving.

## Logistic Regression Model

We selected a Logistic Regression model due to the clarity of the results. We will build, train and evaluate the model to predict team performance using historical data from the league itself. We were able to source comprehensive league data for all previous seasons in csv format. We used data from 2010-2018 as training data and data from 2019 season as testing data.
 We will use such features as team rankings, win percentages as home team, games in the premier league, average league ranking, average team salary by player and momentum.
Our model was designed to find a clear winner in each match (a binary result).
Our model was organized by Home Team and Away Team results. Results were assigned a “1” or a “0”. From a Home Team perspective; “1” designates Win, “0” designates Loss or Draw. From an Away Team perspective; “0” designates Win, “1” designates Loss or Draw.
Betting in English premier league matches is generally split in to “Win” or “Did not win” for the favored team, negating draws as an important factor.
Win-Not Win data was used for the 20 current English premier league teams over their most recent league seasons.
We tested the model using the 2019 data and made predictions for the four games happening on October 17th, 2020.

## Data discrepencies

We have noticed some discrepancies in the datasets due to the fact that every season 3 teams are relegated and 3 other teams are promoted.  Also, some teams stay long time out of the premier league making it difficult to get enough data for such teams.

## Notebooks
We run two notebooks, a master notebook using data from 2011 to 2018 for training and data from 2019 for testing. A prediction notebook that uses data from 2011 to 2019 for training and data from 2020 for test by predicting the result of the four matches playing on October 17th, 2020. Our model correctly predicted the result of two of the four games.


