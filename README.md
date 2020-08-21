# School_District_Analysis


## Overview of the school district analysis: Explain the purpose of this analysis.
This analysis project was performed to modify an earlier analysis of school district student data, which included writing Python code to analyze math and reading scores, school size, budget and school type for a dataset of over 39,000 students across 15 schools.  For this analysis project, a subset of student data (all of the math and reading scores from Thomas High School 9th graders) was removed per the school board's request, and we repeated the analysis, modifying the code to recalculate the student math and reading score metrics as well as summary data, without some specific student data. The purpose of removing the specific student data is to give the school board a clearer picture of score performance and summary metrics without data they consider may be have been altered, and may not be reliable.

missing data 

## Resources

### Data source provided: 
* schools_complete.csv 
* students_complete.csv

### Software utilized:
* Python Version 3.7.7
* Jupyter Notebooks 6.03
* Anaconda 4.8.4

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

To modify the Python code to remove the Thomas High School 9th grade student math and reading scores, we replaced these students' scores with the "NaN" data type, so that these scores do not factor into the analysis. The removed group was 461 students, 

* How is the district summary affected?
The District Summary shows that removing Thomas High School 9th graders' scores lowers Average Math Score across the District from 79.0 to 78.9. The percentage of students Passing Math drops from 75.0 to 74.8, the percentage Passing Reading drops from 85.8 to 85.7 and the percentage Overall Passing drops from 65.2 to 64.9

* How is the school summary affected?
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
    * Scores by school spending
    * Scores by school size
    * Scores by school type*

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

✓ The purpose is well defined. ✓
 SIX to SEVEN metrics are addressed. 
 ✓ THREE to FOUR major changes are summarized for the school district analysis.