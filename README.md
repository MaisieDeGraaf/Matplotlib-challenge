# Matplotlib-challenge

Overview

This repository contains Python code used to analyze tumor volume data from a study involving various drug regimens tested on mice. The code uses Pandas, Matplotlib, and Scipy libraries to perform data cleaning, statistical analysis, and visualization.


Code Description

Dependencies and Setup

•Pandas, Matplotlib, and Scipy.stats libraries are imported for data manipulation, visualization, and statistical calculations.

•Data files (Mouse_metadata.csv and Study_results.csv) paths are specified.


Data Processing

•Mouse data and study results are read and merged into a single DataFrame.

•Duplicate data related to Mouse ID and Timepoint are identified and handled by dropping duplicate entries.

•Summary statistics are generated for tumor volume across different drug regimens, calculating mean, median, variance, standard deviation, and SEM.


Visualizations

•Bar plots using both Pandas and Matplotlib showcase the distribution of observed mouse timepoints per drug regimen.

•Pie charts demonstrate the distribution of male and female mice in the dataset.

•Box plot displays the distribution of final tumor volumes for specific treatment regimens.

•Line plot showcases tumor volume changes over time for a single mouse under Capomulin treatment.

•Scatter plot and linear regression model illustrate the correlation between mouse weight and average observed tumor volume for the Capomulin regimen.


Usage

•The code provided can be used as a reference for analyzing similar datasets involving drug regimens and tumor volume in mice.

•Data paths can be modified to adapt to different file locations or file formats.

•Visualization parameters and plot styles can be adjusted based on specific requirements.

