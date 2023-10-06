# FIFA World Cup Match Analysis

## Overview

This code performs exploratory data analysis on FIFA World Cup match data from 1930 to 2014 using Python. The data is sourced from a CSV file named `Fifa_world_cup_matches.csv`, containing columns for various match statistics, including date, team names, scores, fouls, cards, possession, attempts, passes, etc.

## Analysis Steps

### 1. Data Loading and Overview

The code loads the data into a Pandas DataFrame and provides an initial overview by displaying the top rows and summary statistics of the dataset.

### 2. Goal Statistics

   - **Histograms of goals scored by each team**: Visualizes the distribution of goals scored by individual teams across matches.
   - **Histogram of goal difference**: Illustrates the distribution of the goal differences between teams in matches.

### 3. Correlation Analysis

   - **Heatmap of correlation matrix**: Visualizes the correlations between various match statistics, providing insights into their relationships.

### 4. Visualizations

   - **Scatterplot of possession vs goals**: Examines the relationship between possession and the number of goals scored.
   - **Boxplots of fouls by each team**: Shows the distribution of fouls committed by each team.
   - **Distplots of yellow cards by each team**: Displays the distribution of yellow cards received by each team.
   - **Line plot of red cards over time**: Shows the trend in the number of red cards given in matches over the years.
   - **Bar plot of penalties scored**: Presents the number of penalties scored in the World Cup matches.

### 5. Scatterplot Matrix

   - **Scatterplot matrix of possession, goals, attempts, and passes**: Provides a comprehensive view of the relationships between these key match statistics.

## Requirements

The code relies on the following Python libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Usage

To utilize this code, simply run the script. The output will be displayed inline if executed in a Jupyter notebook. This analysis will help you gain insights into the FIFA World Cup match data, allowing you to explore the performance of teams, the dynamics of matches, and the relationships between various match statistics.
