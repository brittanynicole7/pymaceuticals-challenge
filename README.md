##Overview

For this challenge, we were tasked with merging two datasets and cleaning the DataFrame by removing a mouse with duplicate entries. We also were asked to develop summary statistics for tumor volume (mean, median, variance, standard deviation, and standard error) for each of the drug regimens. We were asked to create a bar chart using Pandas and pyplot to display the number of timepoints per drug regimen. Similarly, we were asked to create a pie chart displaying the distribution of the female versus male mice using Pandas and pyplot. For four drugs (Capomulin, Ramicane, Infubional, and Ceftamin), we were asked to determine if there were any outliers in the tumor volume values and create a box plot for these four drugs. We were asked to create a line plot for one mouse on Capomulin showing the association between tumor volume and timepoints. Lastly, we were asked to create a scatterplot, calculate the correlation coefficient, and create a regression line comparing mouse weight and average tumor volume for the Capomulin regimen. 

##Results

- One mouse had duplicate entries or multiple entries from the same timepoints and this mouse was dropped. 

- Summary statistics for mean and median tumor volume, tumor volume variance, tumor volume standard deviation, and tumor volume standard error for each of the drug regimens are displayed below.

- The Capomulin and Ramicane drug regimens had a higher total number of timepoints compared to other drug regimens. 

- The distribution of gender in the sample was fairly even (Males = 50.96% and Females = 49.04%). Pie charts are displayed below showing the distribution.

- Only one drug regimen of the four selected (Capomulin, Ramicane, Infubinol, and Ceftamin) had potential outliers regarding tumor volume. Infubinol had two potential outlier tumor volume values. The box plot showing the outliers is displayed below. 

- A line plot is also depicted below for one mouse (mouse l509) showing the  size of the mouse’s tumor volume over a number of days. The line plot shows an increase in tumor volume until the 20th day and then a steep drop off following the 20th day. Tumor volume starts to increase again after roughly the 35th day. 

- A scatter plot is also depicted below along with the correlation value and regression line showing the relationship between mouse weight and average tumor volume for the Capomulin regimen. Weight and average tumor volume are highly positively correlated indicating that the more the mouse weighs, the larger their average tumor volume. 
