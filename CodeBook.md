# Getting and Cleaning Data Final Project

### Step 1: Raw input variables
* <b>fit_features</b>:         raw data from features.txt
* <b>fit_activity_labels</b>:  raw data from activity_labels.txt
* <b>fit_X_test</b>:          raw data from X_test.txt
* <b>fit_y_test</b>:           raw data from y_test.txt
* <b>fit_subject_test</b>:    raw data from subject_test.txt
* <b>fit_X_train</b>:         raw data from X_train
* <b>fit_y_train</b>:          raw data from y_train.txt
* <b>fit_subject_train</b>:    raw data from subject_train.txt

### Step 2: Test & Trial union variables
* <b>fit_X</b>:               combination of fit_X_test and fit_X_train
* <b>fit_Y</b>:              combination of fit_y_test and fit_y_train
* <b>fit_subject</b>:          combination of fit_subject_test and fit_subject_train

### Step 3: Set column names for fit_X and fit_activity_labels

### Step 4: Get columns with standard deviation or mean
* <b>fit_cols</b>:            a list of the columns which have "mean(" or "std(" in it.
* <b>fit_X_sub</b>:            same as fit_X, but with only the subset of columns wiht mean and std

### Step 5: Add in our Subject and Activity values.
* <b>fit_XY</b>:               a column binding of fit_X_sub and fit_Y
* <b>fit_XY_dtab</b>:          a data table conversion of fit_YX (which is a data frame)

## Step 6:  Create the averages set
* <b>fit_XY_averages</b>:      a data table containing the averages for each Activity/Subject.

## Step 7:  Formatted output
* <b>fit_output</b>:            a copy of fit_XY_dtab with the Activity names called out
* <b>fit_output_averages</b>:  a copy of the mean and std values, with Activity names included
