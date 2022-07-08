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

![image](https://user-images.githubusercontent.com/30300621/177911451-5fdeeed0-3eb0-445e-9c30-2aca428b89e1.png)

![image](https://user-images.githubusercontent.com/30300621/177911482-3f373a3f-4885-4506-a6e5-771cc77d6c66.png)


## Math and Reading Scores by Grade

![image](https://user-images.githubusercontent.com/30300621/177911896-ff08e5d7-a6bf-42b2-9c7f-cdd457d3570a.png)

![image](https://user-images.githubusercontent.com/30300621/177911942-604ece3d-f100-4583-b8ce-56e9e4fdfbca.png)

![image](https://user-images.githubusercontent.com/30300621/177912007-daeb6fe9-c776-4053-9ae3-6730c554c420.png)

## Scores by School Spending

![image](https://user-images.githubusercontent.com/30300621/177912301-fca13b80-c8be-4467-a0ab-ac63b9c0958c.png)

![image](https://user-images.githubusercontent.com/30300621/177912353-db654387-d7c2-4aa4-ba51-d242d7856174.png)

## Scores by School Size

![image](https://user-images.githubusercontent.com/30300621/177912514-29c1c16e-3c65-4d96-8fc8-f62cce1af2ff.png)

![image](https://user-images.githubusercontent.com/30300621/177912557-b7ab7c4d-50a3-4f7b-842e-e04e63980e91.png)

## Scores by School Type

![image](https://user-images.githubusercontent.com/30300621/177912725-0422f7e2-e0b7-44e5-9486-13d5a745b37e.png)

![image](https://user-images.githubusercontent.com/30300621/177912801-c7fcef8f-553f-443d-ac29-1f9b660601c6.png)


## Summary: 


1. The District Summary was affected by the cleanup

    - Before the cleanup, Thomas High School had an overall passing percentage of 91%
    - After the cleanup, Thomas High School had an overall passing percentage of 65%

2. The School Summary was affected by Thomas' High school ranking dropping from 2nd to 8th in the District. 

3. The Scores by School Size category was not affected significantly. There was very little change in the average math and reading scores after the 9th grade data was changed to NaNs. 

4. The same can be added for Scores by School Type. There was very little change in the average math and reading scores after the 9th grade data was changed to NaNs.

