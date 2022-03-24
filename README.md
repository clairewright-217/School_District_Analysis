# School_District_Analysis

## Project Overview

A city school district needs help analyzing the standardized testing performance of the schools and students within its district. The analysis then needed to be updated to exlude the ninth grade students from Thomas High School because the school board found signs of academic dishonesty, and the grades for these students seemed to have been altered. The following was provided in the original analysis:

### District Summary
1. Total Number of Schools
2. Total Number of Students
3. Total School Budget of District
4. Average Math Score across District
5. Average Reading Score across District
6. % of Students in District Passing Math
7. % of Students in District Passing Reading
8. % of Students Overall Passing

### Schools Summary
1. School Type (District or Charter
2. Total Students per School
3. Total School Budget
4. Per Student Budget
5. Average Math Score
6. Average Reading Score
7. % Students Passing Math
8. % Students Passing Reading
9. % Students Overall Passing

### Specialized Analysis
1. Top Five Performing Schools
2. Bottom Five Performing Schools
3. Average Math and Reading Scores by Grade
4. Group Scores by School Spending per Student
5. Group Scores by School Size
6. Group Scores by School Type

Then this analysis was redone with the data from ninth graders at Thomas High School excluded from the analyzed dataset. 

## Resources
Data Sources: 
- [schools_complete_csv](Resources/schools_complete_csv)
- [students_complete_csv](Resources/students_complete_csv)

Software: Python 3.9.7, Pandas 1.3.4, Conda 4.11.0, Jupyter Notebooks, Visual Studio Code 1.64.2 (Universal)

## Results


How is the district summary affected?
The district summary changed very little after the ninth graders from Thomas High School were removed from the analysis. All measures besides the Average Reading Score were slightly lower (<1%) after the ninth graders were removed, while the Average Reading Score in the district didn't change at all. 

_Original School District Summary (including Thomas HS 9th graders):_

![district_summary_original](Resources/district_summary_original)


_Revised School District Summary (excluding Thomas HS 9th graders):_

How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type















