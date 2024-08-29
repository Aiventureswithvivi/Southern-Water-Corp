# Southern Water Corp Case Study
The goal of this case study was to leverage statistical analysis to proactively detect pump failures and help the Engineering Team manage their resources more effectively. I utilized minute-by-minute time-series data to analyze the behavior of the desalination plant pumps before and during failures.

## Overview of the Analysis
Descriptive Statistical Analysis: I explored various statistical methods to identify trends and behaviors that could indicate pump failure. This involved analyzing raw data and transformed datasets (30-Minute Rolling Mean and 30-Minute Standard Deviation) to gain insights into pump performance.

Inferential Statistical Analysis: I examined correlations between variables to predict potential pump failures, adding another layer of analysis to understand the underlying patterns.

## Key Techniques and Tools Used
Throughout this project, I employed several statistical and data analysis techniques:

* Line Plots and Box Plots: I created visual representations to identify trends and detect outliers in the data.
* Descriptive Statistics: Using the .describe() function, I summarized the central tendency, dispersion, and shape of the dataset's distribution.
* Outlier Detection and Removal: I applied methods to identify and filter out outliers, ensuring a more accurate analysis.
* Data Subsetting and Filtering: I efficiently managed and manipulated dataframes to focus on relevant subsets of data.
* For Loops: I used loops to automate repetitive tasks and streamline the analysis process.
* Dual Axes Plotting: I employed dual-axis plots to visualize multiple variables on separate axes for comparative analysis.
* Correlation Coefficients and Heatmaps: I assessed relationships between variables to uncover patterns and potential predictors of pump failure.
* Linear Regression Models: I built and evaluated regression models to understand the strength of relationships between variables and the outcome of interest.
