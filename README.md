# pymaceuticals
Data Insights

1) Capomulin treatment is highly promising, as it had the second lowest mean and median tumor volume. It also had a standard deviation of 4.99, which was the second lowest, indicating that the values are clustered close to the mean. Although Ramicane provided lower tumor values, the difference was very slight and requires further analysis between the two drugs to determine if Ramicane is significantly more effective at reducing tumor volume than our test drug.

2) Mouse l509 seems to have experienced some mixed results from Capomulin. As the course of treatment progressed until about the halfway timepoint, the mouse's tumor volume consistently increased. After day 20, we begin to see a downward trend in tumor volume with a one slight increase at day 30, which is then followed by a large decrease. However, we then begin to see another spike at day 40. It would be interesting to observe this mouse's tumor trend to see if there are increases, but it may also be a waste of time since it is possible that this mouse is an outlier and not reflective of the sample as a whole.

3) The correlation coefficient between mouse weight and average tumor volume is 0.84. Since this value is close to 1, there is a strong positive relationship between the two variables. As average tumor volume increases, mouse weight increases. This makes sense, as an increase in volume would add more weight to the mouse.

Instructions:
Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.


Use the cleaned data for the remaining steps.


Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.



Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.



Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.


Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.


Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
