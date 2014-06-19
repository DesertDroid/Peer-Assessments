Peer-Assessments
================

Getting and Cleaning Data Course Project

- Download data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip to your working directory.
- Unpack the data.
- Rename the folder "UCI HAR Dataset" to folder "data".
- Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
- Execute the script run_analysis.R from working directory.
- Two output files are generated in the current working directory:
  - cleanedData.txt - a data frame called cleanedData with 10299*68 dimension.
  - meansData.txt - a data frame called result with 180*68 dimension.
- Use data <- read.table("./meansData.txt") command in RStudio to read the final tidy data.
