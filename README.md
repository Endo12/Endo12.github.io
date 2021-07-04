# [Movie Analysis](https://endo12.github.io/)

A step-by-step tutorial on how to analyze movie data from Kaggle.com regarding American Superhero and Japanese Animated movies, complete with both code and
real-time output to improve clarity. Project was coded in Python via Jupyter Notebook and converted internally to HTML. Project hosting for this site is done 
locally through Github pages and can be accessed [here](https://endo12.github.io/). The tutorial takes the viewer various steps of the Data Pipeline, including
Data Collection (loading data from Kaggle), Data Tidying (removing extraneous data and renaming columns) and Exploratory Data Analysis. The EDA consists of
analyzing rating scores via basic data analysis, such as pie charts and histograms, analyzing box office performance via scatterplots and budget efficiency
graphs, and verifying box office performance results with hypothesis testing.

The following packages were used to create this project:

## Pandas

Used to organize, store, and quickly retrieve data. Pandas was the most used package in this project, due to the aforementioned reasons, as well as the inbuilt
methods in Pandas that allow for easy graphing for fast data analysis.

## Numpy

Used for creating linear trendlines for various scatterplots during basic data analysis.

## MatPlotLib

Used to create sub plots for each scatterplot of data. Allowed me to effortlessly create multiple graphs for the same set of data, but select different movie 
genres and dependent variables, and organize all the subgraphs on one page. This package also enabled quick graph setting changes, like title and size changes.

## Seaborn

Used to create violinplots in one command, allowing for fast checks of the data's residuals to determine normality.

## StatsModel

Used to execute linear regression and ANOVA tests on subsets of the data 
