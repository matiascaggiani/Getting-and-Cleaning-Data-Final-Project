# Getting and Cleaning Data: Course Project


## Introduction

In this repository you will find my work for the final project of the Coursera "Getting and Cleaning Data". 

### About the raw data

The 561 features are not labeled and can be found in the x_test.txt, activity labels can be found inthe y_test.txt and the test subjects can be found in the subject_test.txt. All the same applies for the training set. 

### About the script and the tidy dataset

The scriptcalled run_analysis.R will merge the test and training datasets. To succesfully run this script you will need:

*the UCI HAR Dataset extracted
*arrange the working directory

After merging, labels are added and only mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

About the Code Book

The CodeBook.md file explains the transformations performed and the resulting data and variables.
