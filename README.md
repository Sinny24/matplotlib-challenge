# matplotlib-challenge
You've recently joined Pymaceuticals, Inc., a specialized pharmaceutical company focusing on anti-cancer medications. The company initiated a study to screen potential treatments for squamous cell carcinoma (SCC), a prevalent form of skin cancer.

As a senior data analyst, you have access to the complete data from their latest animal study. The study involved 249 mice diagnosed with SCC tumors, receiving various drug regimens. Over 45 days, tumor development was observed and measured. The primary objective was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

The executive team has assigned you to generate all necessary tables and figures for the technical report of the clinical study. Additionally, they expect a top-level summary of the study results.

This assignment involves the following tasks:

1. Prepare the data by merging the mouse_metadata and study_results DataFrames into one. Check for unique mouse IDs and remove any duplicate time points to create a cleaned DataFrame.

2. Generate summary statistics, including mean, median, variance, standard deviation, and SEM of the tumor volume, categorized by drug regimen.

3. Create two bar charts representing the total number of time points for each drug regimen using both Pandas DataFrame.plot() and Matplotlib's pyplot methods.

4. Generate two pie charts to display the distribution of female versus male mice in the study, using both Pandas DataFrame.plot() and Matplotlib's pyplot methods.

5. Calculate quartiles and interquartile range (IQR) for the final tumor volume of mice treated with the most promising drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin). Identify potential outliers and create a box plot to visualize the distribution.

6. Create a line plot to show the tumor volume versus time point for a mouse treated with Capomulin.

7. Generate a scatter plot displaying the correlation between tumor volume and mouse weight for the Capomulin treatment regimen.

8. Calculate the correlation coefficient and perform linear regression analysis to understand the relationship between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the scatter plot.

By completing these tasks, you'll provide valuable insights and visual representations of the study results to support Pymaceuticals' research efforts in developing effective anti-cancer medications.
