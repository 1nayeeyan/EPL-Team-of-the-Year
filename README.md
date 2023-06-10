# EPL-Team-of-the-Year

## Introduction

The purpose of this analysis project is to determine which players qualify to be on the English Premier League Team of the Year for the 2022-2023 season. The squad will consist of the starting 11, the top 11 players will begin on the pitch, with 8 players additionally sitting on the bench. Starting on the pitch will be 1 goalie, 4 defenders, 3 midfielders and 3 forwards. The bench will house a goalie, 2 defenders, 3 midfielders and 2 forwards, meaning the team of the year will have 2 goalies, 6 defenders, 6 midfielders, and 5 forwards.

## Procedure

The plan is to use a web scraper to download relevant player data from https://fbref.com/en/comps/9/Premier-League-Stats, and other indexes of the site, clean, conduct analysis and then visualize my findings.

## Criteria

Since each position has different requirements for their skillset, I have outlined the key performance indicators for each position as follows:

### Goalkeepers:

  - Clean Sheets: The number of matches in which a goalkeeper did not concede any goals.
  - Save Percentage: The percentage of shots on target that the goalkeeper saves.
  
### Defenders:

  - Tackles Won: The number of successful tackles made by a defender.
  - Interceptions: The number of times a defender successfully intercepts a pass.
  - Clearances: The number of times a defender clears the ball away from dangerous areas.
  = Successful Passes: The accuracy and number of completed passes by a defender.
  
### Midfielders:

  - Pass Accuracy: The percentage of successful passes made by a midfielder.
  - Key Passes: The number of passes that directly lead to a goal-scoring opportunity.
  - Successful Dribbles: The number of successful dribbles past opponents.
  - Goals and Assists: The number of goals and assists contributed by a midfielder.
  
### Forwards:

  - Goals Scored: The number of goals scored by a forward.
  - Assists: The number of goals directly set up by a forward.
  - Shots on Target: The number of shots by a forward that are on target.
  - Conversion Rate: The percentage of shots that result in goals.

We are also going to filter based on the criteria that a player must have played at least 1500 minutes in the entirety of the season.
