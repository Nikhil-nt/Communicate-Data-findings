# Filghts Dataset

## Dataset Overview

This dataset reports flights in the United States, including carriers, arrival and departure delays and reasons for delays for the year 1987.

## Summary of Findings

I am intrested to find out the features involved in the arrivals delay of the flight. To investigate the ArrDelay I would take the help of additional variables like distance, departure delay and diverted. I have taken the first step of Univariate exploration where i represented indiviaual variables on a histogram,the first variable was ArrDelay where i had to reduce the bin size to make it look spread.
The second variable is Distance variable there was a transformation which i had taken to make the distribution look normal.
The 3rd variable was DepDelay variable which was a normal distribution.

The second investigation was bivariate where i explored the relationship in the pairs of the variables.Scatterplot,being the first visualisation, is used to plot 2 numeric variables the arrival delay did not increase as the distance between the cities increased,and showed no correlation.To investigate further i choosed the line plot and got the same results.
The second observation was between Arrival and departure delay which showed positive correlation. The arrival delay showed significant increase due to increase of departure delay.
The last observation was between distance and departure delay which showed no relationship.

Third investigation was multivariate where heatmaps ,pairplots and scatterplots with positional encodings are used to check the relationship between 3 or more variables. A scatterplot with 3 variables ,ArrDelay,DepDelay,Distance is plotted and i found relationships between DepDelay and ArrDelay.
I have plotted Pairgrid plots in the 2nd step to further investigate ,out of 16 plots there correlation between DepDelay and ArrDelay
The last step was heatmaps which gave me the same results. 

## Key Insights for Presentation

I would recommend line plot and the heatmaps to polish for my presentation.In the bivariate investigation i would recommend line plots for DepDelay and ArrDelay.Line plots are clean and easy for anyone to understand. it clearly shows the correlation of 2 variables.

For multivariate exploration, i would prefer heatmaps because pairplots and scatterplots with positional encodings would be confusing heatmaps shows that darker boxes means it has stronger relationship and a color legend is also given on the right side also shows the depth of relationship based on the color darkness making it easier to understand. The further investigation through multivariate plots satisfies the condition results of bivariate exploration.

## Requirements
* Numpy 
* Pandas
* Matplotlib
* Seaborn


