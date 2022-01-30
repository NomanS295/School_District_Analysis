
# School District Analysis

In this project we are performing an analysis using school and student data to inform a school district on their budget and priorities.


## Main Objectives
1. Learn about Jupyter Notebook and open them from local directories 
2. Read an external CSV file into a DataFrame.
3. Format a DataFrame column along with retrieving data from specific columns of the dataframe
4. perform multiple calculations on dataframe
 
## Purpose

A school district asked for an analysis of several key metrics by each school campus and by the district level. The analysis focused mostly on math and reading scores and after reviewing the data it was suspected that there was acedemic dishonesty taking place in the grade 9th class. The school board asked for the data to be removed so it could be analyzed again for a recomparison.


 ## Results
 ### How is the district summary affected?
Original analysis:

![Screenshot_4](https://user-images.githubusercontent.com/96362530/151686596-fce902cc-fb71-4c6d-82db-a15290e0e927.png)


Revised analysis:
![Screenshot_5](https://user-images.githubusercontent.com/96362530/151686618-a893ed8e-7495-4e52-bb74-dbe828ae8d10.png)

The change is less than 1% and all the passing percentages are still nearly the same number. with this we can conclude that the district summary was not affected by much.

### How is the school summary affected?
In the original analysis, Thomas High School started with a 91% overall passing rate, which is very high and unusual. after the data was revised and readjusted. there was a more realistic passing percentage.
Original analysis:
![Screenshot_6](https://user-images.githubusercontent.com/96362530/151686791-6d897890-06c1-480f-b6d2-5a6ae1ff0402.png)

Revised analysis: 

![Screenshot_7](https://user-images.githubusercontent.com/96362530/151686827-ddecb523-65d4-4ad9-b27d-eb6c95d3b873.png)

There is nearly a 31% difference after the analysis of the overall passing rate

###How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board but after the analysis was adjusted thomas was ranked eighth place.
## How does replacing the ninth-grade scores affect the following:
### Adjusted Averages using the Math and Reading Scores 

In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. these are the updated average math and reading scores
 
![Screenshot_10](https://user-images.githubusercontent.com/96362530/151687553-b2ef6988-6176-49a4-8931-1bc3eec287b6.png)
![Screenshot_11](https://user-images.githubusercontent.com/96362530/151687555-1d97dc21-c90b-430f-a4f7-686f21c2c90f.png)

### Scores by school spending

Thomas High School did not have many changes in spending even after the data was adjusted from the original

Original:
![Screenshot_12](https://user-images.githubusercontent.com/96362530/151687663-80933614-2777-4ddd-b0e3-b2b5e4838dbc.png)

Revised: 

![Screenshot_13](https://user-images.githubusercontent.com/96362530/151687671-86d6a18b-d81a-4914-be1c-bf73d94b1f10.png)
### Scores by school size
Thomas High School is a medium sized school. there wasnt much difference between the original and revised data analysis in this field.
original analysis:
![Screenshot_14](https://user-images.githubusercontent.com/96362530/151687809-415c96e8-c22b-4d25-88fd-e11b298c6ec3.png)
revised analysis:
![Screenshot_15](https://user-images.githubusercontent.com/96362530/151687811-4d84506c-644f-44ec-99a9-7bc489e7b75b.png)


### Scores by school type

Thomas High School is a charter school type and there was very little impact to the type even after changing the grade scores.

original:
![Screenshot_18](https://user-images.githubusercontent.com/96362530/151688112-4a9cdd6d-4055-4bda-97d8-ecd0af0c3555.png)
revised:
![Screenshot_19](https://user-images.githubusercontent.com/96362530/151688117-0ba61a28-7706-4883-be57-93c1fc4a0dec.png)


## Summary of the data:

1. The overall passing rate for Thomas High School changed dramatically from 91% to 65% after revision

2. Thomas High School's ranking dropped from 2nd to 8th.

3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School  

4. the campus math and reading averages and passing percentages all saw shifts throughout the analysis






