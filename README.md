# Loan Data Analysis Project

# Overview

This project is a Python-based data analysis tool designed to explore and visualize loan data. It processes two datasets: test_Y3wMUE5_7gLdaTN.csv and train_u6lujuX_CVtuZ9i.csv, utilizing various visualization techniques to uncover patterns and relationships within the data.

The primary script, loan.py, performs the following tasks:

Reads and preprocesses data: Loads the CSV files into DataFrames and performs initial exploration.

Visualizes data distributions: Creates histograms and bar charts for column-wise data.

Generates correlation matrices: Displays relationships between numerical columns.

Plots scatter and density plots: Visualizes pairwise relationships for numerical features.

# Files

loan.py: The main Python script for data analysis and visualization.

test_Y3wMUE5_7gLdaTN.csv: A dataset containing test loan data.

train_u6lujuX_CVtuZ9i.csv: A dataset containing training loan data.

# Features

1. Data Distribution Visualization

Function: plotPerColumnDistribution(df, nGraphShown, nGraphPerRow)

Purpose: Generates histograms or bar charts for columns with 1 to 50 unique values.

2. Correlation Matrix

Function: plotCorrelationMatrix(df, graphWidth)

Purpose: Creates a heatmap showing correlation coefficients between numerical columns.

3. Scatter and Density Plots

Function: plotScatterMatrix(df, plotSize, textSize)

Purpose: Produces scatter and density plots for numerical features, annotating correlation coefficients.

# How to Run

Ensure Python and required libraries (pandas, numpy, matplotlib, sklearn) are installed.

Place loan.py, test_Y3wMUE5_7gLdaTN.csv, and train_u6lujuX_CVtuZ9i.csv in the same directory.

Execute loan.py using Python:

python loan.py

Outputs include visualizations displayed inline, showing distributions, correlations, and pairwise relationships.

# Example Outputs

Distribution Plots:

Histograms for numerical data.

Bar charts for categorical data with limited unique values.

Correlation Matrix:

Heatmap highlighting relationships between features.

Scatter and Density Plots:

Pairwise relationships annotated with correlation coefficients.

# Requirements

Python 3.x

Libraries:

pandas

numpy

matplotlib

sklearn

# Contributing

Feel free to suggest improvements or add new features by submitting a pull request or opening an issue.

