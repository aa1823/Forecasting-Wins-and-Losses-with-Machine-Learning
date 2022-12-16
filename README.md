# Forecasting Wins and Losses with Machine Learning





## \| Brief History

I got the idea to do this project from a previous project I did in my STAT 632 class. In that presentation I tried to model the relationship between Points Per Game and several other predictors.

## \| Context

| The data set for this analysis comes directly from [basketball reference](https://www.basketball-reference.com/teams/LAL/2023_games.html).

-   Specifically it is the Lakers' average game data for the 2019-2020 regular season. I was interested in doing this analysis because that season was interrupted by the COVID-19 pandemic, leading the regular season for all teams to end at 73 games instead of the typical 82 game season.

-   At the time of the pandemic, the Lakers had only played 63 games as did other teams, and when it resumed they played an additional 10 games, not including a truncated playoffs. I was interested to see if there would be any differences between the pandemic games versus if the pandemic never happened.

**So, to do this I am interested in forecasting Wins and Losses based on four predictors: Team points, Opponent Points, and Games played with W/L as the response variable.**


## Results 

From the simulation, I was able to conclude that had the Lakers played all 82 games, they would have won 55 games, and lost 27, with a final win percentage of 67% and a loss percentage of 33%.

- This is lower than what they actually achieved during the truncated regular season, which was 49 W (78%) and 14 L (22.2%) out of 73.
