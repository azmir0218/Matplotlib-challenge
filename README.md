# Matplotlib - The Power of Plots

## Background/Objective
<img width="592" alt="Screen Shot 2021-10-28 at 6 29 10 PM" src="https://github.com/azmir0218/Matplotlib-challenge/blob/main/Laboratory.jpg">

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. 

## Tasks to complete:

* Checked the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Used the cleaned data for the remaining steps.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.


* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.


* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.


* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Ploted the linear regression model on top of the previous scatter plot.

* Wrote at least three observations or inferences that could be made from the data. Included these observations at the top of notebook.

##Tools Used:
NumPy, SciPy, Matplotlib, Jupyter Notebook, Pandas


