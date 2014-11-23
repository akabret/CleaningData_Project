# Getting and Cleaning Data Final Project

### Step 1: Raw input variables
* fit_features         raw data from features.txt
* fit_activity_labels  raw data from activity_labels.txt
* fit_X_test           raw data from X_test.txt
* fit_y_test           raw data from y_test.txt
* fit_subject_test     raw data from subject_test.txt
* fit_X_train          raw data from X_train
* fit_y_train          raw data from y_train.txt
* fit_subject_train    raw data from subject_train.txt

### Step 2: Test & Trial union variables
* fit_X                combination of fit_X_test and fit_X_train
* fit_Y                combination of fit_y_test and fit_y_train
* fit_subject          combination of fit_subject_test and fit_subject_train

### Step 3: Set column names for fit_X and fit_activity_labels

### Step 4: Get columns with standard deviation or mean
* fit_cols             a list of the columns which have "mean(" or "std(" in it.
* fit_X_sub            same as fit_X, but with only the subset of columns wiht mean and std

### Step 5: Add in our Subject and Activity values.
* fit_XY               a column binding of fit_X_sub and fit_Y
* fit_XY_dtab          a data table conversion of fit_YX (which is a data frame)

## Step 6:  Create the averages set
* fit_XY_averages      a data table containing the averages for each Activity/Subject.

## Step 7:  Formatted output
* fit_output            a copy of fit_XY_dtab with the Activity names called out
* fit_output_averages  a copy of the mean and std values, with Activity names included
