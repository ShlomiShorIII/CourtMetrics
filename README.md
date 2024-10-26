# NBA Statistics Analysis Tool

This tool connects to the NBA statistics API (`nba_api`) and provides customized insights based on user-defined settings. By simply specifying a player, team, and season, users can view historical and season-specific data for teams and players in the NBA.

## Features

1. **Conference Standings**: View the standings for both the Eastern and Western Conferences based on the selected season.
2. **Player Statistics History**: Access a comprehensive table detailing the career statistics of the chosen player.
3. **Player Performance Graphs**: Visualize season-by-season stats with line graphs for points, rebounds, and assists.
4. **Team Rankings Over Time**: See how the selected team has ranked in each season since the year 2000.

## How It Works

The software loads user settings from a text file (`settings.txt`), where the user inputs:
- Player name
- Team name
- Season of interest

Using these inputs, the tool retrieves the relevant data from the NBA statistics API and presents it in easy-to-read tables and graphs.
