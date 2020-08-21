# School_District_Analysis


## Overview of the school district analysis: 
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

## Results: 

To modify the Python code to remove the Thomas High School 9th grade student math and reading scores, we replaced these students' scores with the "NaN" data type, ![New_Student_count](./Additional_resources/Reading&Math_scores_replacedwith_Nan.png)  so that these scores do not factor into the analysis. The removed group was 461 students, ![THS_9thGraders_count](./Additional_resources/Thomas_HS_9th_Grade_student_count.png) which bring the total student count down to 38,709 from 39,170

![New_Student_count](./Additional_resources/New_student_count-after_removing_THS_9thgraders.png) 

* How is the district summary affected?

The District Summary shows that removing Thomas High School 9th graders' scores lowers Average Math Score across the District from 79.0 to 78.9. The percentage of students Passing Math drops from 75.0 to 74.8, the percentage Passing Reading drops from 85.8 to 85.7 and the percentage Overall Passing drops from 65.2 to 64.9

**Original District Summary**
![Original_District_Summary](./Additional_resources/Original_District_Summary-sameprecision.png) 

**Modified District Summary**
![Modified_District_Summary](./Additional_resources/Modified_District_Summary.png) 


* How is the school summary affected?

The School Summary table shows some much larger effect from having removed the Thomas High School 9th graders. Average math and reading scores at Thomas High School dropped a few basis points, while the percentage of students passing math and reading dropped by around 25 percentage points. 

* Average Math Scores: Decrease from 83.41 to 83.35
* Average Reading Scores: Increase from 83.83 to 83.89
* % Passing Math: Large decrease from 93.27 to 66.91
* % Passing Reading: Large decrease from 97.30 to 69.66
* %Overall Passing: Large decrease from 90.94 to 65.07

**Original School Summary**
![Original_School_Summary](./Additional_resources/Original_per_School_Summary.png) 

**Modified School Summary**
![Modified_School_Summary](./Additional_resources/Modified_per_School_Summary.png) 


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Comparing the modified data analysis to the original analysis shows that Thomas High School's student performance dropped significantly. The percentages of students passing math, reading or passing both decreased by about 25% which indicates the 9th grader's scores really moved those metrics higher for the school.

* How does replacing the ninth-grade scores affect the following:

Replacing the Thomas High School 9th grader scores with null values only takes these grades out of the metrics analyzed, all ofthe grade levels are unaffected.

* Math and reading scores by grade are unaffected, other than those for 9th graders at Thomas High School, whose scores have been removed

![Orig_MathScores_byGrade](./Additional_resources/Original_mathscores_bygrade.png) 

![Modified_MathScores_byGrade](./Additional_resources/Modified_mathscores_bygrade.png) 


    

    * Scores by school spending
Scores by school spending are unaffected

![Orig_Spending](./Additional_resources/Original_Spending_by_scores.png) 

![Modified_Spending](./Additional_resources/Modified_Spending_by_scores.png) 
    
    * Scores by school size
Scores by school size are unaffected
![Orig_Size](./Additional_resources/Original_Size_by_scores.png) 

![Modified_Size](./Additional_resources/Modified_Size_by_scores.png) 


    * Scores by school type*

![Orig_Type](./Additional_resources/Original_SchoolType_by_scores.png) 

![Modified_Type](./Additional_resources/Modified_SchoolType_by_scores.png) 


## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

✓ The purpose is well defined. ✓
 SIX to SEVEN metrics are addressed. 
 ✓ THREE to FOUR major changes are summarized for the school district analysis.