## Contents ##
This repository contains all the necessary files and information to analyze 2000s-2010s animated Disney movie reviews. It contains a Data, Scripts, and Output folder where the user can find all of the csv files used to obtain the reviews, as well as scripts used for transforming and analyzing the final dataset. The repository also contains the README (this file) and the LICENSE markdown files, as well as the final presentation slides for the project. 

## Section 1: Software and platforms used 
The Python programming language was used for all analysis and coding for this project. The VADER package needs to installed and used to analyze the reviews and obtain the sentiment scores for this project. Additional packages that need to be installed include: pandas, datetime, matplotlib.pyplot, spicy, numpy, statsmodels, and seaborn. Both Mac and Windows platforms were used in this project.

## Section 2: Map of documentation 
The Project1_DS4002 repository contains the following folders and files:
1. Data folder: contains the Final Datasets subfolder, where the merged and cleaned datasets (DisneyMoviesDataset.csv and FinalDisneyDataset.csv) can be found. It also contains the Individual Movie Data folder, where one can find data for each individual Disney movie utilized in the study. Finally, the folder contains the Data Appendix pdf document, named DataAppendix.pdf.
2. OUTPUT folder: Contains png files of output from exploratory data analysis (EDA), data visualizations, and regressions. This includes any boxplots, bar graphs, and other visualizations the group has created for analysis.
3. SCRIPTS folder: contains three ipynb files which were created by the group to investigate the research question using statistical analysis. The scripts involve data cleaning and creation, EDA, and data analysis.
4. Final project presenation slides (Group 15 Project 1 Presentation.pdf)
5. LICENSE markdown file
6. README markdown file

## Section 3: Instructions for reproducing results. 
To replicate the methods and results of this study, one can find all the necessary tools and files from this GitHub repository. After accessing the repository, the user can download all the data from the Data folder. The 1DatasetCreationAndCleaning.ipynb file must be run first in a coding environment such as Google Colab. This file merges the individual Disney movie datasets into one cohesive dataset, and it also cleans the dataset including dropping unnecessary variables. Next, the 2EDA.ipynb file can be run to obtain the same results from EDA that the group did. Although not imperative to the analysis for this study, the EDA portion serves as additional context into the research question and dives deeper into the variables used in the dataset. Finally, the 3Analysis.ipynb file must be run to obtain results using statistical analysis, such as running a t-test, running a regression, and using confidence intervals.
