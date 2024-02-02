# Capstone-Project-Python & Tableau

## NBA Data Analysis, with particular focus on the LA Lakers Project

## Overview/Project/Goals

This project involves the analysis and visualization of NBA datasets provided by the NBA stats website. The dataset covers the years 2003-2022.


Basketball Game Analysis Using Python and Tableau

Table of Contents

1.  Dataset Information
2.  Project Structure
3.  Requirements
4.  Setup Instructions
5.  Data Exploration
6.  Visualizations
7.  Dashboard Creation
8.  Results/Key Findings
9.  Challenges
10. Future Work
11. References


##Dataset Information

Analyzed 5 datasets (csv files):

- **Source:** NBA Stats website
- **Data Range:** 2003-2022
- **Format:** csv 

The initial datasets are listed below:

- games.csv : all games from 2004 season to last update with the date, teams and some details 	like number of points, etc.
- games_details.csv : details of games dataset, all statistics of players for a given game.
- players.csv : players details (name).
- ranking.csv : ranking of NBA given a day (split into west and east).
- teams.csv : all teams of NBA.


After data cleaning and preprocessing, the merged dataset is listed below:

- **Merged Dataset Name:** finalLAL2.csv

This project uses the several datasets merged to create the finalLAL2.csv dataset, which contains detailed statistics from basketball games. Key columns include game dates, team IDs, points scored, field goal percentages, rebounds, assists, and more. The dataset spans the 2003 to 2022 season and includes data for both home and visitor teams.


##Project Structure

The project is structured as follows:

data/: Folder contains the five (5) initial datasets and the merged the dataset file, finalLAL2.csv.

scripts/: Contains Tableau workbooks and any preprocessing scripts.

docs/: Presentation.

README.md: This file, containing project information and instructions.


##Requirements

Tableau Desktop or Tableau Public
Python (for  data preprocessing)


##Setup Instructions

- Install Tableau Desktop or Tableau Public.
- Clone this repository or download the provided files.
- Open the Tableau workbook included in the scripts/ directory to view the visualizations and dashboard.


##Data Exploration

An initial exploration of the dataset includes:

- Understanding the structure of the data.
- Identifying key metrics like points scored, assists, rebounds, etc.
- Checking for missing or inconsistent data.


##Visualizations

Below visualizations were created to analyze different aspects of the data:

- Points Scored Over Time
- Win-Loss Ratio for Home Team
- Average Rebounds by Teams
- Field Goal Percentage Comparison
- Points Distribution in Games
- Assist to Turnover Ratio
- Free Throw Accuracy Over Time
- Three-Point Success Rate
- Opponent Analysis
- Team Performance Dashboard

Each visualization provides unique insights into the game's performance metrics.


##Dashboard Creation

A comprehensive dashboard is created to aggregate the visualizations, offering an interactive and holistic view of the data. The dashboard includes filters for teams, dates, and other relevant metrics.


##Results/Key Findings

- LA Lakers had their most NBA wins in a calendar year (86) in 2008. Conversely, they had their fewest wins (19) in the 2015.
- The LA Lakers had their highest 3-point success rate (38.19%) in 2017 and had their lowest 3-point accuracy (30.64%) in 2003. 
- The LA Lakers attempted their highest amount of 3-point shots (42) in 2017 and attempted their lowest 3-point shots (26) in 2011. 


##Challenges

- Data type correction required after EDA and modelling on Jupyter lab.
- Forecasting Reliability: had to forecast even with 2022 data been incomplete (ended at the close of the 2021/2022 season).
- Dashboard Design Complexity: Designing an effective and user-friendly dashboard to meet diverse stakeholder needs and preferences.


##Future Work

- Explore additional features of the datasets for more comprehensive analysis, including player-specific analysis and impact on team results.
- Perform more visualizations to better interpret the data and get better deductions.
- Refine visualizations and dashboard layout for better user experience.


##References

- https://www.tableau.com/trial/tableau-software 
- https://www.nba.com/stats
- https://www.kaggle.com/datasets/nathanlauga/nba-games?resource=download



