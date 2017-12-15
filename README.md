# Getting-and-Cleaning-Data-Course-Project

This repository contains the following files:
- 'run_analysis.R': R script that contains the logic to read raw data and output tidy data set.
- 'tidy.txt': Text file that contains the final tidied data set produced by 'run_analysis.R'.
- 'CodeBook.md': Markdown file containing description of variables in 'tidy.txt'.

##'run_analysis.R'
1. Downloads required dataset.
2. Extracts only the required activity and feature information.
3. Load train and test datasets.
4. Merge datasets
5. Transform required columns into factors
6. Outputs 'tidy.txt'