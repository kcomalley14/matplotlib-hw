# Pymaceuticals - Matplotlib Homework
This particular dataset was comprised of two different csv files for study results including timepoint, tumor volume, and metastatic sites, as well as mouse data that includes drug regimen, sex, age, and weight. These were able to be merged by 'Mouse ID'. The larger, merged dataset made it very easy to find the following data:
* Summary statistics table for mean, median, variance, standard deviation, and SEM of tumor volume for each drug.
* Bar plots for total mice per drug regimen using DataFrame.plot() as well as pyplot that is imported with matplotlib.
* Pie plots comparing female versus male mice in the study by using DataFrame.plot() and pyplot again.
* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
* Generated a line plot for a specific mouse and the tumor volume over time with drug Capomulin.
* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 
* Plot the linear regression model on top of the previous scatter plot.