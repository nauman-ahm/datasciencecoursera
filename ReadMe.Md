# Getting and Cleaning Data course project

## All these comments are already present in run_analysis.R

## Step 1: Download the raw data from given website
## Step 2: Set working directory to "UCI Har Dataset/train"
## Step 3: Reading the "subject_train.txt", "X_train.txt", and "y_train.txt" files
## Step 4: Merging the 3 DF's into 1 Data Frame and removing unwanted DF'S
## Step 5: Set working directory to "UCI Har Dataset/test"
## Step 6: Reading the "subject_test.txt", "X_test.txt", and "y_test.txt" files
## Step 7: Merging the 3 DF's into 1 Data Frame and removing unwanted DF'S
## Step 8: Change directory to "UCI Har Dataset"
## Step 9: Script to read the "features.txt" file and remove the numbers on features DF
## Step 10: Script to add the col names to train_set and test_set
## Step 11: Adding identifier column prior to merge
## Step 12: Merging training and test sets into one data set and removing unwanted DF's
## Step 13: Adding descriptive labels to activity_label and rearranging
## Step 14: Removing all the unwanted data (keeping only means and stds)
## Step 15: Script to create second dataset with only means 
## Step 16: Writing means_summary to a txt file
