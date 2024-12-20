# The Court-Side Effect: Exploring the Relationship Between NBA Team Performance and Game Attendance

## 📖 Project Overview
This project, developed for **COGS 108 (Data Science in Practice)**, investigates whether an NBA team's performance influences game attendance. \
Specifically, we analyzed data spanning from the 2001 to 2023 NBA seasons to uncover trends and relationships between team wins, Elo ratings, and attendance.

## 🎯 Objectives
- **Primary Goal**: Analyze the relationship between team performance (measured by wins and Elo ratings) and game attendance.
- **Secondary Goals**:
  - Understand the impact of home-court advantage and team consistency on attendance.
  - Assess trends in attendance over time and anomalies, such as the COVID-19 pandemic's effect.

## 🛠️ Features
- Data collection and cleaning for NBA attendance and performance metrics.
- Utilized **Ordinary Least Squares (OLS) regression** to identify the key predictors of game attendance.
- Visualization of trends using Python libraries like Matplotlib and Seaborn.
- Analysis of anomalies, such as attendance drops during COVID-19 pandemic.

## 📂 Repository Structure
-  data/: Contains datasets used for the analysis
-  checkpoints/: Jupyter Notebooks with exploratory data analysis and intermediate progress
-  FinalProject_Group159-FA24.ipynb: Finalized Juptyer Notebook with complete analysis and findings
- README.md: Project description (this file)

## 📊 Methodology

1. **Data Collection**:
   - Gathered NBA performance and attendance data for the 2001-2023 seasons.
   - Addressed anomalies, such as the impact of COVID-19 on attendance numbers.
2. **Data Cleaning & Preprocessing**:
   - Removed missing values and normalized the key metrics, such as wins and Elo ratings.
3. **Analysis**:
   - Performed exploratory data analysis to visualize trends.
   - Applied OLS regression to evaluate the statistical signifance of performance metrics.
4. **Key Findings**:
   - **Elo ratings** were positively linked to game attendance, while the number of wins alone was not statistically significant when controlling for Elo.
   - Fans are more drawn to consistent, high-performing teams rather than those with occasional wins.

## 🎥 Project Walkthrough
[![Public Video](https://i3.ytimg.com/vi/ufqs22C-_wo/maxresdefault.jpg)](https://www.youtube.com/watch?v=ufqs22C-_wo)

## 🔭 Future Investigation
This project provided insights into the relationship between NBA team performance and game attendance, but there are additional areas for future exploration: 
   1. **Player Level Analysis**: 
       - Investigate and analyze player statistics and their correlation with fan engagement.
   2.  **External Factors**: 
        - Explore the influence of external factors, such as ticket pricing, marketing strategies, or economic conditions on attendance trends.
        - Assess the impact of regional factors, such as city population, local income levels, and city funding.
   3. **Advanced Machine Learning Models**: 
        - Implement more complex models to predict attendance based off of a broader range of variables.
        - Use time-series analysis to forecast future attendance trends.