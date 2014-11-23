# Getting and Cleaning Data Final Project

This is a seven-step process to import and consolidate wearable computing data.

Input data:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

* First, we input the raw data into a series of eight variables.
* Second, we union threetrial and test data sets into unified data sets.
* Third, we set thecolumn names for the fit_X and fit_activity_label variables.
* Fourth, we identify the mean and standard deviation columns that we want to pass along.
* Fifth, we add our Subject and Activity values to our raw test data.
* Sixth, we create averages for each Subject/Activity metric.
* Seventh, we create output data sets that include the Activity strings (e.g., Walking, Running).

* The final data is written to <b>fit_output</b> and <b>fit_output_averages</b>.

