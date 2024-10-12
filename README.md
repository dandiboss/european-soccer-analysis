European Soccer Database Analysis
Overview
This project involves an in-depth analysis of the European Soccer Database using SQL queries. The goal is to extract meaningful insights regarding match statistics, player fitness, and team performance. The findings aim to facilitate further analysis and modeling.

Table of Contents
Project Description
Data Source
Queries and Analysis
Installation
Usage
Conclusions


Project Description
The European Soccer Database contains comprehensive data about soccer matches, teams, and players across various leagues. This analysis aims to explore trends in goal scoring, player health (via BMI), and overall league performance using a series of SQL queries.

Data Source
The data used in this project is sourced from the European Soccer Database, which includes the following tables:

Leagues
Match
Player
Team

Queries and Analysis
1. Date Range of Matches
Objective: Determine the time interval of the dataset.
Query: Calculated the number of days between the oldest and most recent matches using the DATE_DIFF function.
2. Home Goals Statistics
Objective: Aggregate statistics related to home goals scored for each season and league.
Metrics:
Minimum, maximum, average, total home goals scored.
Mid-range home goals.
3. Unique Seasons Count
Objective: Count the unique seasons present in the match table to provide an overview of the timeframe.
4. Matches Played by League
Objective: Determine the number of matches played by each league in each season.
5. Player BMI Calculation
Objective: Calculate the Body Mass Index (BMI) for players and assess their fitness levels.
Result: Extracted players with an optimal BMI (18.5 - 24.9).
6. Non-Optimal BMI Players Count
Objective: Identify players not falling within the optimal BMI range.
7. Team Goals Analysis
Objective: Identify the team with the highest total goals during the most recent season.
8. Seasonal Top Teams
Objective: Determine the top-scoring team for each season.
9. Top Scoring Teams Table
Objective: Create a table of the top 10 teams based on total goals scored.
10. Pair Combinations of Top Teams
Objective: Show all possible pair combinations of the top 10 teams to facilitate match-up comparisons.

Conclusions
This SQL analysis on the European Soccer Database provides valuable insights into match statistics, player fitness, and team performance. The findings can serve as a foundation for further investigations, such as predictive modeling for future matches or deeper dives into player health trends.

Installation
To run this analysis, you will need access to a SQL environment that supports the queries written in this project. If you're using a local setup, ensure you have the necessary database installed and the tables populated with data.

Usage
Clone the repository to your local machine.
Open your SQL client.
Execute the queries found in the queries.sql file to retrieve insights from the database.

License
This project is licensed under the MIT License - see the LICENSE file for details.




