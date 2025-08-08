# Data Cleaning and Visualization of the Student Performances Dataset

## Overview of Project
This project focuses on cleaning up the data of the **Student Performances** data set so that it can be used for Machine Learning as well as visualizing the important columns of the data via different graphs

## Dataset Source
- Source: UC Irvine Machine Learning Repository (https://archive.ics.uci.edu/)
- Dataset link: https://archive.ics.uci.edu/dataset/320/student+performance

## Process of Completing the project
1. Data Cleaning
   - Replace all string values with corresponding numbers
   - One-hot encode columns
2. Visualizing Data
   - Chose the columns that I found most interesting
   - Created a heatmap using these columns
   - Chose six columns that I found most relevant and made a pair plot with these columns
   - Created three histograms with the following variables: absences, trimester two grades and trimester three grades
   - Created three regression plots with the following variables:
      - Trimester 1 vs trimester 3
      - Trimester 1 vs trimester 2
      - Trimester 2 vs trimester 3

## Graphs
 - Heatmap:
<img width="1500" height="1200" alt="Student_Performances_Heatmap" src="https://github.com/user-attachments/assets/0edf434a-2661-4b63-8312-b7cada5d1ac5" />

 - Pairplot:
<img width="1500" height="1500" alt="SP_Pair_Plot" src="https://github.com/user-attachments/assets/2f28a5dd-4b18-4f21-9c84-def1e45fb092" />

 - Histograms:
<img width="640" height="480" alt="SP_Histogram_absences" src="https://github.com/user-attachments/assets/a1737cd5-f990-4080-bf3c-5751e43631de" />
<img width="640" height="480" alt="SP_Histogram_G2" src="https://github.com/user-attachments/assets/257d8fda-f182-4c61-82a0-e8debe0595bb" />
<img width="640" height="480" alt="SP_Histogram_G3" src="https://github.com/user-attachments/assets/115ed771-8d1f-478c-9149-12714c6d55de" />

 - Regression plots:
<img width="640" height="480" alt="SP_Regression_G1_vs_G2" src="https://github.com/user-attachments/assets/ae23435a-38b8-4270-8e7f-4162f395bf5b" />
<img width="640" height="480" alt="SP_Regression_G2_vs_G3" src="https://github.com/user-attachments/assets/a7f94705-96a2-4ca2-9442-321ba612608a" />
<img width="640" height="480" alt="SP_Regression_G1_vs_G2 (1)" src="https://github.com/user-attachments/assets/a6679128-98ac-471f-973a-75b53261f4ce" />


## Language and Libraries:
 - Language: Python
 - Libraries:
   - Pandas
   - Matplotlib
   - Seaborn
