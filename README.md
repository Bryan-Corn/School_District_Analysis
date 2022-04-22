# School_District_Analysis
Bootcamp Module 4 (Python, Anaconda, Pandas)

Analysing standardized test scores for school district 

# Overview

## Purpose

Maria, Cheif Data Scientist for Py City School District has asked me to help analiyze standardized test scores for each of the high schools in the Py City School District. This analysis will help the school board glean insights into performance trends and inform discussion regarding strategic descisions at the school and district level.

## Resources

Software: Python v3.7.11, Anaconda v4.12.0, Pandas

## Deliverables
Maria has asked for the following deliverables for the school district analysis and the deliverable is shown under each section of requests: 
```
- A high-level snapshot of the district's key metrics, presented in a table format:
  • Total number of students
  • Total number of schools
  • Total budget
  • Average math score
  • Average reading score
  • Percentage of students who passed math
  • Percentage of students who passed reading
  • Overall passing percentage
```
My analysis produced the following:
![image](/Analysis/district_analysis_deliverable_1.png, "High-level District Snapshot")

```
- An overview of the key metrics for each school, presented in a table format
```
![image](/Analysis/district_analysis_deliverable_2.png, "School Summary Table")

```
- Additional tables presenting each of the following metrics:
  • Top 5 and bottom 5 performing schools, based on the overall passing rate
  • The average math score received by students in each grade level at each school
  • The average reading score received by students in each grade level at each school
  • School performance based on the budget per student
  • School performance based on the school size 
  • School performance based on the type of school
```
![*based on overall passing rate](/Analysis/district_analysis_deliverable_3.png, "Top 5 and Bottom 5 Performing Schools)




```
- Create new DataFrame for District Summary:
  • Total number of schools in the column "Total Schools"
  • Total number of students in the column "Total Students"
  • Total budget in the column "Total Budget"
  • Average reading score in the column "Average Reading Score"
  • Average math score in the column "Average Math Score"
  • Percentage of students passing reading in the column "% Passing Reading"
  • Percentage of students passing math in the column "% Passing Math"
  • Overall passing percentage in the column "% Overall Passing"
  ```
  
# Results
```
  Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
```
  
```
- Create a new DataFrame for each school in the district
  • School name
  • School type
  • Total students
  • Total school budget
  • Per student budget
  • Average math score
  • Average reading score
  • % passing math
  • % passing reading
  • % overall passing
```
# Summary
```
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
```
