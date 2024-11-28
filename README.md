# project_week5_6
# Data Analytics: EDA, Inferential Stats & Tableau 

Welcome to Project 2 - Customer Experience (CX) Team at Vanguard

## Project Overview

You are a newly hired data analyst in the Customer Experience (CX) team at Vanguard, a US-based investment management company.
You've been thrown right into the deep end with your first task. Before your arrival, the team launched an exciting digital experiment. Now, they’re eagerly awaiting the results and need your help!

## Research question

Would these changes encourage more clients to complete the process?

## Experiment

An A/B test was set into motion from 3/15/2017 to 6/20/2017 by the team.

Control Group: Clients interacted with Vanguard’s traditional online process.
Test Group: Clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

The goal is to see if the new design leads to a better user experience and higher process completion rates.

## Hypotheses

1. The median time for the Test group is equal to or greater than the median time for the Control group.
2. The mean time for the Test group is equal to or greater than the mean time for the Control group
3. The completion rate for the Test group is greater than for the Control group.


## Data Tools

There are three datasets that will guide your analysis:

1. Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients.
2. Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2. It’s recommended to merge these two files prior to a comprehensive data analysis.
3. Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment.


## Tools and Resources

- **Jupyter Lab**: An open-source tool for interactive data analysis and visualization.
- **Python**: The primary language used for data processing, cleaning, and analysis.
- **Python Libraries**:
    - `pandas` for data manipulation.
    - `numpy` for numerical operations.
    - `matplotlib`, `plotly` and `seaborn` for data visualization.
    - `scipy.stats` for statistical analysis.
- **Tableau**: A tool for transforming raw data into dashboards, making complex data analysis accessible.


## Files Hierarchy

**data_files**
- raw: Raw data containing the complete test information.
- clean: Cleaned data after dropping null values, filtering, and performing calculations.

**notebooks**
- Jupyter notebooks with Python code and functions for cleaning and plotting information.

**tableau**
- Tableau files with plots and dashboards.

## Conclusions

1. Although the completion rate is higher for the Test group, the difference is not statistically significant.
2. The median duration for completing the test is significantly shorter for the Test group compared to the Control group.
3. We cannot conclude that the mean duration differs significantly between the two groups.
4. The average error rate increased slightly between the Control and Test groups, although the difference was not statistically significant.
5. Users in the Test group encountered significantly more errors on Step 1 compared with the Control group.
6. Step 3 is where customers spend the most time; therefore, the "Vanguard" UX team should focus on simplifying this step to improve user experience.

### GitHub Repo

https://github.com/mjpacko/project_week5_6/

### Presentation Link

The slides were made using Canva and present in the following link:
https://www.canva.com/design/DAGXlvnnZyw/fT6DRv3LBbPQ6XGh4Fc4rg/edit

### The Team

- Álvaro
- Moana
