---
title: "ReadMe"
author: "Gaurav Chawla"
date: "Monday, August 25, 2014"
output:
  html_document:
    keep_md: yes
---

This file describes how run_analysis.R script works.

1) First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".

2) Make sure the folder "data" and the run_analysis.R script are both in the current working directory.

3) Second, use source("run_analysis.R") command in RStudio.

4) Third, you will find two output files are generated in the current working directory:
   merged_data.txt and data_with_means.txt 
   
5) Finally, use data <- read.table("data_with_means.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject, and there are 6 activities in total and 30 subjects in total, we have 180 rows with all combinations for each of the 66 features.

