# MLB Stolen Bases Analysis: Impact of the 2023 Rule Changes
## Project Overview
Major League Baseball introduced several rule changes in 2023, including larger bases, a pitch clock, and limits on pickoff attempts. These changes were designed in part to encourage more action on the basepaths.

This project investigates whether those rule changes had a measurable impact on stolen base activity and offensive production across MLB.

## Research Questions
Did stolen bases per game increase after the 2023 rule changes?

Did stolen base success rates improve?

Did increased stolen base activity lead to more runs scored?

## Data
The analysis uses historical MLB team-level data from the Lahman Baseball Database.

## Key variables analyzed:
Stolen Bases (SB)

Caught Stealing (CS)

Runs Scored (R)

Games Played (G)

Data was aggregated by season to evaluate league-wide trends over time.

## Methodology
Data Preparation

Aggregated team statistics into league-wide yearly totals

Calculated Stolen Base Success Percentage

Calculated Stolen Bases Per Game

Calculated Runs Per Game

Classified seasons as:

Pre-Rule Changes (2000–2022)

Post-Rule Changes (2023–Present)

Statistical Analysis

Welch's Two-Sample t-tests were used to determine whether differences between the pre-rule-change and post-rule-change periods were statistically significant.

## Visualization
Line charts were created to visualize:

Total stolen bases by season

Stolen Base Percentage by season

Runs by season

Stolen Bases per game by season

Stolen bases per game versus runs per game

<img width="1014" height="547" alt="Stolen_Bases_By_Year" src="https://github.com/user-attachments/assets/b60c8aaf-e516-48b2-9563-374635c095f9" />
<img width="1061" height="547" alt="sb_r_g" src="https://github.com/user-attachments/assets/7ada276f-5121-423f-af37-3bfb4dc71c8c" />


## Key Findings
Stolen Bases Increased Significantly

The introduction of the 2023 rule changes was associated with a substantial increase in stolen bases per game.

Stolen Base Success Rates Improved

Teams were not only attempting more steals, but were also succeeding at a higher rate than in previous seasons.

Runs Scored Did Not Increase Significantly

Although stolen base activity increased significantly, the analysis did not find strong statistical evidence that runs scored per game increased as a result.

## Tools Used
Python

Pandas

Matplotlib

Seaborn

SciPy

Jupyter Notebook

Skills Demonstrated

Data Cleaning

Data Transformation

Exploratory Data Analysis (EDA)

Statistical Hypothesis Testing

Data Visualization

Sports Analytics

Python Programming

## Future Improvements
Analyze team-level differences in stolen base adoption

Examine player-level stolen base trends

Investigate additional offensive metrics such as:

On-Base Percentage (OBP)

Runs Created

Weighted On-Base Average (wOBA)

Expand analysis as additional post-rule-change seasons become available
