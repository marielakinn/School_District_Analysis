# School District Analysis

## Project Overview
In this projected we helped Maria, the Chief Data Scientist for a shcool district, clean, sort, and analyzed two data sets containing information of different schools and their students. 

The analysis consited of:

- Generating a school district summary (number of students, number of schools, total budget, score averages, passing percentages)
- Generating a school summary (student count per school, budget per student, score averages per school, passing percentages per school)
- Finding high and low performing schools 
- Finding average math and reading scores by grade
- Grouping scores by school spending per student
- Grouping scores by school size
- Groupong scores by school type

After the completion of the above, we were informed that reading and math grades for Thomas High School ninth graders appeared to be altered, and our analysis had to be modified so the results exclude data of that specific group of students.

### Purpose

The purpose of this analysis is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. After completing this, we will repeat the school district analysis, and recreate the metrics previously found.

## Results

- How is the district summary affected?

  The student count decreased from 39,170 to 38,709, and the average math acore slightly dropped from 79.0 to 78.0.
  Please see below screenshot of the results prior to replacing data for nine graders:

![](Resources/District_analysis_original.PNG)


Please see below screenshot of the results after replacing data for nine graders:

![](Resources/District_analysis_nan.PNG)


- How is the school summary affected?

Most of the averages for Thomas High School were impacted. Despite the change in the averages is small, the % overall passing dropped from 90.95% to 90.63%

Please see below screenshot of the results prior to replacing data for nine graders:
  ![](Resources/School_summary_original.png)

Please see below screenshot of the results after replacing data for nine graders:
  ![](Resources/School_summary_nan.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  Because we excluded the grades from 9th graders, Thomas High School remained in the #2 position.However, their % overall average slightly decrease from 90.95 to 90.63.
  
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    
    ![](Resources/mathbygrade_nan.png)
    
    ![](Resources/readingbygrade_nan.png)
    
  - Scores by school spending
    
    ![](Resources/School_spending_original.PNG)
    ![](Resources/School_spending_nan.PNG)


  - Scores by school size
    ![](Resources/School_size_original.PNG)
    
    ![](Resources/School_size_nan.PNG)


  - Scores by school type


    ![](Resources/School_type_nan.PNG)
    
    ![](Resources/School_type_nan.PNG)


## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.



The analysis should contain the following:

Overview of the school district analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
