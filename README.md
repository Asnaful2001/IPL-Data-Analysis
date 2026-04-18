# 🏏 IPL Data Analysis (2008–2025)

## Overview
A complete data cleaning and exploratory analysis project on IPL match data using Python and Pandas.
This project covers 1,158 matches and 134,190 ball-by-ball deliveries across all IPL seasons.

## Dataset
- `matches.csv` — Match level data including teams, venue, toss, result
- `deliveries.csv` — Ball by ball data for every match
- `players.csv` — Player profiles including role, batting/bowling style
- `seasons.csv` — Season level summary statistics

## What I Did
### 🧹 Data Cleaning
- Fixed missing values across all 4 datasets
- Standardized column names
- Converted date columns to proper datetime format
- Labeled valid nulls meaningfully (e.g. no wicket = 'not_out')

### 📊 Analysis & Visualizations
1. Top 10 Teams by Total Wins
2. Toss Decision Impact on Match Outcome
3. Top 10 Run Scorers across all seasons
4. Top 10 Wicket Takers across all seasons
5. Total Runs Scored per IPL Season

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Author
**Asnaful**
