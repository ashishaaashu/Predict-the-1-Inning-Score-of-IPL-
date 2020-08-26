# Predict-the-1-Inning-Score-of-IPL-
Objective- Build a model to predict the first innings score of any IPL match

#Algorithms Used
• Linear Regression
• Decision Tree Regression
• Random Forest Regression
• Adaptive Boosting (AdaBoost) Algorithm

#Dataset consists following columns:
• mid: Unique match id.
• date: Date on which the match was played.
• venue: Stadium where match was played.
• batting_team: Batting team name.
• bowling_team: Bowling team name.
• batsman: Batsman who faced that particular ball.
• bowler: Bowler who bowled that particular ball.
• runs: Runs scored by team till that point of instance.
• wickets: Number of Wickets fallen of the team till that point of instance.
• overs: Number of Overs bowled till that point of instance.
• runs_last_5: Runs scored in previous 5 overs.
• wickets_last_5: Number of Wickets that fell in previous 5 overs.
• striker: max(runs scored by striker, runs scored by non-striker).
• non-striker: min(runs scored by striker, runs scored by non-striker).
• total: Total runs scored by batting team at the end of first innings.
