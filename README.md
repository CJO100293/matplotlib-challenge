# matplotlib-challenge
## **Background:**

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

# **Sources:**
## **Starter Code Section:**

The basis for the code used in the "# Get the duplicate mice by ID number that shows up for Mouse ID and Timepoint." step was found from https://github.com/redeat17/Matplotlib-Challenge/blob/master/pymaceuticals_starter.ipynb

The basis for the code used in the "# Create a clean DataFrame by dropping the duplicate mouse by its ID." step was found with the help of AskBCS as well as https://sparkbyexamples.com/pandas/pandas-isin-explained-with-examples/ and https://stackoverflow.com/questions/14057007/remove-rows-not-isinx

the basis for the alternative code used in the "# Alternate method to accomplish the same as above:" which is commented out in the "# Create a clean DataFrame by dropping the duplicate mouse by its ID." step was done with the assistance of Steve Bennett.

## **Summary Statistics Section:**

the basis for the code used in the "# Using the aggregation method, produce the same summary statistics in a single line" step was found from https://pandas.pydata.org/pandas-docs/version/0.22/generated/pandas.core.groupby.DataFrameGroupBy.agg.html

## **Bar and Pie Charts Section:**

The basis for the code used in the "# Generate a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using Pandas." step was worked on with Tyler White in a study group and AskBCS

The basis for the code used in the "# Generate a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using pyplot." step was worked on with the help of AskBCS.

The basis for the code used in the "# Generate a pie plot showing the distribution of female versus male mice using pyplot" step was helped out with by AskBCS.

## **Quartiles, Outliers and Boxplots Section:**

The basis for the code used in the "# Start by getting the last (greatest) timepoint for each mouse" step was worked out with the help of https://www.sweetstudy.com/questions/matplotlib-challenge

The basis for the code used with my "outliers" variable in the "# Determine outliers using upper and lower bounds" step was worked out with the help of https://www.nagwa.com/en/videos/985101043283/ and https://towardsdatascience.com/outlier-detection-part1-821d714524c

The basis for the code used in my "# Setting marker colors and size" section of the "# Generate a box plot that shows the distrubution of the tumor volume for each treatment group." step was found at https://matplotlib.org/3.1.1/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py and https://stackoverflow.com/questions/43342564/flier-colors-in-boxplot-with-matplotlib with the help of AskBCS