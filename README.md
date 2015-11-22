# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity and feature info
3. Load both the training and test datasets, keeping only the columns which reflect a mean or standard deviation
4. Load the activity and subject data for each dataset, and merge the columns with the dataset
5. Merge the two datasets
6. Convert the `activity` and `subject` columns into factors
7. Create a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8. The output result is stored in the file `tidyDataset.txt`.
