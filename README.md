# Analysis-on-Meteorological-Data
Performing Analysis of Meteorological Data

Performing Analysis of Meteorological Data
Photo by Markus Spiske on UnsplashLet us understand what is Meteorology. Meteorology is a branch of the atmospheric sciences which includes atmospheric chemistry and atmospheric physics, with a major focus on weather forecasting.
  You can find the data-set on Kaggle (Source URL: https://www.kaggle.com/muthuj7/weather-dataset). We are going to use NumPy, pandas and matplotlib libraries of Python to import, extract, clean, transform and plot.

Hypothesis of the Analysis:"Has the Apparent temperature and humidity compared monthly across 10 years of the data indicate an increase due to Global warming."

Step 1:
Let's start by importing libraries:
To make use of the functions in a module, you'll need to import the module with an import statement. An import statement is made up of the import keyword along with the name of the module.

Step 2:
Reading data-set using pandas library:
A data-set is a collection of data. In the case of tabular data, a data set corresponds to one or more database tables, where every column of a table represents a particular variable, and each row corresponds to a given record of the data set in question. In this scenario we are going to read weather History data.

Step 3:
Cleaning dataset:
Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. Dropping unwanted data and converting it according to our requirement.
* We need to analysis data yearly. We need to convert Formatted Date into datetime format. We will do it by using pandas method to_datetime() . Also, we will set Formatted Date as the index to the data-set and resample our data.

Step 4:
Plotting of Data:
The purpose of plotting data is to visualize variation or show relationships between variables. We will now plot the line graph to display Average Humidity and Average Apparent Temperature over 10 years (2006–2016).
*We will now plot the line graph to display average temperature and humidity for all 12 months over the 10 years period. Let's start from First month of the year.

1)January:
2) February:
3) March:
4) April:
5) May:
6) June:
7) July:
8) August:
9) September:
10) October:
11) November:
12) December:
For more knowledge refer https://en.wikipedia.org/wiki/Meteorology.

Conclusion: As we can see in the above images there are many ups and downs in the temperature. So, we can conclude that global warming has caused an uncertainty in the temperature over past 10 years while the average humidity has remained constant throughout the 10 years.
