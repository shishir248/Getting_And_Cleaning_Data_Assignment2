# Getting-and-Cleaning-Data-Project-2

This repository deals with the second project of the course Getting and Cleaning Data by Coursera. It has analysis on Human Activity recognition dataset and related instructions.

Dataset is available at- https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# Files Included

1. Codebook.md- It is a codebook to describe all the variables, instructions and any other work which I have performed for the project.

2. run_analysi.R- It performes the following- 
    
    i. Download the dataset from web if it does not already exist in the working directory.
    
    ii. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
    
    iii. Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names          to descriptive. (-mean to Mean, -std to Std, and remove symbols like -, (, ))
    
    iv. Extract data by selected columns(from step 3), and merge x, y(activity) and subject data. Also, replace y(activity) column to it's         name by refering activity label (loaded step 3).
    
    v. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity. The result is            shown in the file tidy_dataset.txt.
 
 3. FinalData.txt- Exported final data.
