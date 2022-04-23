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
![sadfdfgdfgdfg](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable_1.png)

```
- An overview of the key metrics for each school, presented in a table format
```

![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable__2.png "School Summary Table")

```
- Additional tables presenting each of the following metrics:
  • Top 5 and bottom 5 performing schools, based on the overall passing rate
  • The average math score received by students in each grade level at each school
  • The average reading score received by students in each grade level at each school
  • School performance based on the budget per student
  • School performance based on the school size 
  • School performance based on the type of school
```
Top 5 Performing Schools (based on overall passing rate):

![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable__3.png "Top 5 Performing Schools (based on overall passing rate)")

Bottom 5 Performing Schools (based on overall passing rate):

![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable__4.png "Bottom 5 Performing Schools (based on overall passing rate)")

Average Math Score by Grade:

![Average Math Score by Grade](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable__5.png "Average Math Score by Grade")

Average Reading Score by Grade:

![Average Reading Score by Grade](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable_6.png "Average Reading Score by Grade")

School Performance based on Budget Per Student:

![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable__7.png "School Performance based on Budget Per Student")

School Performance based on Size:

![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable_8.png "School Performance based on Size")

School Performance based on Type:

![Average Reading Score by Grade](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable_9.png "School Performance based on Type")

### While putting the deliverables toger, Maria updated her request. Thomas High School has been found to have misrepresented the scores for 9th grade reading and math and would like these datapoints removed. She would like an updated District Summary with the new data.
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
High-Level District Snapshot (after correcting data):

![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Analysis/district_analysis_deliverable_10.png "High-Level District Snapshot (after correcting data)")
 
  
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
