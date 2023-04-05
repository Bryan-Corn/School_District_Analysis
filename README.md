![image](https://github.com/Bryan-Corn/School_District_Analysis/blob/main/Resources/Test.png)
# School_District_Analysis


Analysing standardized test scores for school district 

# Overview

## Purpose

Maria, Cheif Data Scientist for Py City School District has asked me to help analiyze standardized test scores for each of the high schools in the Py City School District. This analysis will help the school board glean insights into performance trends and inform discussion regarding strategic descisions at the school and district level.

## Resources

Software: Python v3.7.11, Anaconda v4.12.0, Pandas, Jupyter Notebooks

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
![image](/Analysis/district_analysis_deliverable_1.png "High-level District Snapshot")

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

![Top 5 Performing Schools](/Analysis/district_analysis_deliverable__3.png "Top 5 Performing Schools (based on overall passing rate)")

Bottom 5 Performing Schools (based on overall passing rate):

![image](/Analysis/district_analysis_deliverable__4.png "Bottom 5 Performing Schools (based on overall passing rate)")

Average Math Score by Grade:

![Average Math Score by Grade](/Analysis/district_analysis_deliverable__5.png "Average Math Score by Grade")

Average Reading Score by Grade:

![Average Reading Score by Grade](/Analysis/district_analysis_deliverable_6.png "Average Reading Score by Grade")

School Performance based on Budget Per Student:

![image](/Analysis/district_analysis_deliverable__7.png "School Performance based on Budget Per Student")

School Performance based on Size:

![image](/Analysis/district_analysis_deliverable_8.png "School Performance based on Size")

School Performance based on Type:

![Average Reading Score by Grade](/Analysis/district_analysis_deliverable_9.png "School Performance based on Type")

### While putting the deliverables together, Maria updated her request. Thomas High School has been found to have misrepresented the scores for 9th grade reading and math and would like these datapoints removed. She would like an updated District Summary with the new data.
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

![image](/Analysis/district_analysis_deliverable_10.png "High-Level District Snapshot (after correcting data)")
 
  
# Results

After removing the 9th grade data for Thomas High School and recalculating some of the metrics, several important changes can be seen in the data:
```
Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
```
![High-level District Snapshot](/Analysis/district_analysis_deliverable_1.png "High-level District Snapshot")
![image](/Analysis/district_analysis_deliverable_10.png "High-Level District Snapshot (after correcting data)")

After removing the bad data, the Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing metrics each when down byu a fraction of a percentage point while the Reading Average Score remained the same.

```
How is the school summary affected?
```
![image](/Analysis/district_analysis_deliverable_11.png "Thomas High School Summary")

The top row includes the data that was later removed to create the bottom row. We can see that the average scores for both math and reading remained the same while the three 'passing %' scores show a significant boost.

```
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
```
Thomas High School's relative performance compared to other schools is greatly increased by removing the 9th grade data. Before changing the data, Thomas Hogh School ranked among the lower middle while it now ranks among the top 5 performing schools.

```
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
```
• Math and Reading scores by grade are unchanged other than showing NaN for Thomas High School's 9th grade data

• The $631-645 group got a boost in the passing % columns

• Large(2000-5000) schools also show a boost in % Passing columns as THS averages all incresed to higher scores than the averages in the group.

• Charter Schools, as a group, benefit from the boost in THS's % Passing columns.


# Summary

After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, the average scores for reading and math for the remaining data did not change while the passing percentages in read and math both went up significantly. This change in data also raised the overall passing percentage and gave a boost to each catergory into which THS was placed.

