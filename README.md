# matplotlib_challenge
Assignment 5

This Assignment 5 was created in conda version 4.13.0 in "PythonData" environment using Pandas and Jupyter Noteboook.

The matplotlib_challenge folder contains a "data" folder, a pymaceuticals_starter Jupyter source file that was provided as a guide, and the pymaceuticals Jupyter source file, which is the assignment. Inside the "data" folder are two csv files, "Mouse_metadata" and "study_results" that contain the data for the mouse study.

The two csv files were merged into a single dataframe, and checked for any mouse ID with duplicate time points. The duplicated mose data was removed and a clenaed dataframe was created that was used for the remaining steps.

There were three observations or inferences that were made from the data based on the information generated below:

1. Summary Statistics

	A dataframe with each drug regimen as rows and the  mean, median, variance, standard deviation, and SEM of the tumour volume as columns.
	the information were generated using the  'groupby' method and the 'agg' method.

2. Bar Chart

	The total number of mice tested for each drug regimen throughout the course of the study was plotted as a bar chartfor each drug regimen. 
	Two plots were created using Pandas's 'DataFrame.plot()' method and Matplotlib's 'pyplot' methods.

3. Pie Chart

	The distribution of female or male mice in the study was plotted as a pie chart.
	Two plots were created using Pandas's 'DataFrame.plot()' method and Matplotlib's 'pyplot' methods.

4. Quartiles, Outliers, and a Box Plot

	The final tumour volume of each mouse across four of the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) was calculated.
	A box plot of the final tumour volume for all four treatment regimens was generated using Matplotlib, and the outlier was highlighted.

5. Line Plot

	A line plot of tumour volume vs. time point was plotted for a mouse that was treated with Capomulin.

6. Scatter Plot

	A scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen was generated.

7. Calculation of Correlation and Regression and Plot of Regression Model

	The correlation coefficient and linear regression model between mouse weight and average tumour volume for the Capomulin treatment was determined.
	The linear regression model was added on top of the scatter plot in item 6 above.

