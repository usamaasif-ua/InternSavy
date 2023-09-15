# Cricket World Cup 2019 Player Performance Analysis

This project aims to analyze the performance of cricket players in the Cricket World Cup 2019. The dataset used for this analysis was scraped from ESPN Cricinfo, and it includes data on matches played up until 18th May 2019.

### About the Dataset
The dataset comprises several CSV files, each containing information about different aspects of the Cricket World Cup 2019:

Kaggle Dataset Link: https://www.kaggle.com/datasets/saivamshi/cricket-world-cup-2019-players-data

1. **Batsman Data (df_batsman.csv):** Contains data about batting performance, including runs scored, strike rate, boundaries, and more.

2. **Bowler Data (df_bowler.csv):** Contains data about bowling performance, including overs bowled, maidens, wickets taken, economy rate, and more.

3. **Ground Averages Data (df_ground_avg.csv):** Includes information about the average scores at different cricket grounds.

4. **ODI Match Results Data (df_match_results.csv):** Provides details about the outcomes of ODI matches, including the teams involved and match results.

5. **ODI Match Totals Data (df_match_totals.csv):** Contains data on total runs scored and total wickets taken in ODI matches.

6. **World Cup Players Data (df_wc_players.csv):** Contains information about players participating in the Cricket World Cup 2019.

### Data Preprocessing
Before diving into the analysis, some data preprocessing steps were performed:

- Data types of columns were adjusted.
- Rows with players who did not bat were removed from the Batsman dataset.
- Strings and special characters in numeric columns were replaced to convert them to the appropriate data type.

### Batsman Performance Analysis
In the batsman performance analysis, various aspects of batsmen's performance were explored:

- The top 10 batsmen with the highest number of matches played in the World Cup.
- Analysis of a specific batsman's performance, including their highest score, strike rate, and boundary statistics.
- Analysis of a particular batsman's performance against a specific opponent (e.g., Australia).
- A scatter plot showing the relationship between strike rate and runs scored by batsmen.

### Bowler Performance Analysis
The analysis of bowler performance included:

- Identifying the top 10 bowlers with the most wickets in the World Cup.
- Identifying the top 10 bowlers with the most maiden overs.
- Finding the bowler(s) with the maximum number of overs and the lowest economy rate.
- Creating scatter plots to visualize the relationship between various bowling statistics and the number of wickets taken by bowlers.

These analyses provide valuable insights into the performance of both batsmen and bowlers in the Cricket World Cup 2019.

Please refer to the Jupyter notebook for detailed code and visualizations related to this project.