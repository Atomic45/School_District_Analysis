# School_District_Analysis
## Analysis of School District Data using Python

## SUMMARY

The school board has requested this analysis to locate any academic dishonesty, specifically, reading and math grades for Thomas High School ninth graders. The task has been given to provide a report showing the ninth grade data as NaNs and re-writing the report to find any inconsistencies to the overall analysis. The task will include the following:

1. Replace ninth-grade reading and math scores.
2. Repeat the school district analysis.
3. This written report showing the findings for the school district analysis. 

## GETTING STARTED
### Replace Ninth-Grade Reading and Math Scores

A copy of the original python file "PyCitySchools.ipynb" was renamed to "PyCitySchools_Challenge_testing.ipynb" to test the code provided for this analysis. Numpy was installed prior to using the code provided to allow the use of the Pandas loc method. This method is used to retrieve all the columns and rows in a DataFrame where the condition of True is met using comparison and logical operators. 
The code will look like this: **student_data_df.loc[(student_data_df["reading_score"] >= 70 & (student_data_df["math_score"] >= 70)]**

The next steps (2-4) require replacing the replace the reading and math scores with NaN. 

![image](https://user-images.githubusercontent.com/30300621/177906963-625a460b-22fc-4053-96cf-c12b389a47f2.png)


### Repeat the School District Analysis

<ins>The District Summary</ins>

![image](https://user-images.githubusercontent.com/30300621/177909168-15c75193-ba7a-492b-a78c-e412a759ed9e.png)

![image](https://user-images.githubusercontent.com/30300621/177909228-1f5c8320-a954-49de-85c0-b2cbb895d383.png)

![image](https://user-images.githubusercontent.com/30300621/177909290-668760e6-60f4-4e66-819f-4c94681cdcfe.png)

![image](https://user-images.githubusercontent.com/30300621/177909313-a709745c-3279-40ac-b9cb-2dc3043b9df6.png)


<ins>The School Summary</ins>

![image](https://user-images.githubusercontent.com/30300621/177909516-d21c35b0-16f3-4d8b-9b0b-caeab4ecbf5c.png)

![image](https://user-images.githubusercontent.com/30300621/177909550-949972ed-1df3-46af-bf55-ee186b6746d7.png)

![image](https://user-images.githubusercontent.com/30300621/177909587-1099b1a4-25cc-4f6c-85b7-afd97410a069.png)

![image](https://user-images.githubusercontent.com/30300621/177910927-4debdbb0-9e1a-46c8-8933-058f7cd23d9d.png)

![image](https://user-images.githubusercontent.com/30300621/177910976-c92ccd8c-33f9-4a47-8faa-9af0604bb425.png)


## High and Low Performing Schools
<ins>The top 5 and bottom 5 performing schools, based on the overall passing rate</ins>





<ins>The average reading score for each grade level from each school</ins>

<ins>The scores by school spending per student, by school size, and by school type</ins>

## RESULTS

Using bulleted lists and images of DataFrames as support, address the following questions.

**How is the district summary affected?**

**How is the school summary affected?**

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

**How does replacing the ninth-grade scores affect the following:**

<ins>Math and reading scores by grade</ins>

<ins>Scores by school spending</ins>

<ins>Scores by school size</ins>

<ins>Scores by school type</ins>

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

