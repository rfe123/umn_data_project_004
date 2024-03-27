# umn_data_project_004
Machine Learning Project
https://docs.google.com/presentation/d/1uHyvoO-T4omjag3wL0RJMqRCTAqg18d8OBxQvGjoVs4/edit#slide=id.g2c6cd48d089_0_22

NFL Data was loaded from the Kaggle Competition set - Big Data Bowl 2024
https://www.kaggle.com/competitions/nfl-big-data-bowl-2024/data

ESPN API provides Team information
https://site.api.espn.com/apis/site/v2/sports/football/nfl/teams

Data was transformed using Pandas and loaded to SQLite
  Add a play_uuid column to Plays and Tracking data
  Transpose Tracking Data to single rows for each ball snap
  Calculate Cumulative season statistics for each team and success on conversions
  Merge the Tracking and Plays data together to train 

Multiple Machine Learning approaches were applied and compared - analysis performed to determine whether player position or player performance are better indicators of a first down conversion
