# School_District_Analysis
## Analysis of School District Data using Python

## SUMMARY

The school board has requested this analysis to locate any academic dishonesty, specifically, reading and math grades for Thomas High School ninth graders. The task has been given to provide a report showing the ninth grade data as NaNs and re-writing the report to find any inconsistencies to the overall analysis. The task will include the following:

1. Replace ninth-grade reading and math scores.
2. Repeat the school district analysis.
3. This written report showing the findings for the school district analysis. 

## GETTING STARTED

A copy of the original python file "PyCitySchools.ipynb" was renamed to "PyCitySchools_Challenge_testing.ipynb" to test the code provided for this analysis. Numpy was installed prior to using the code provided to allow the use of the Pandas loc method. This method is used to retrieve all the columns and rows in a DataFrame where the condition of True is met using comparison and logical operators. 
The code will look like this: **student_data_df.loc[(student_data_df["reading_score"] >= 70 & (student_data_df["math_score"] >= 70)]**

