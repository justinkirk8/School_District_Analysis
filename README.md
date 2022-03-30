# School_District_Analysis

## Overview of School District Analysis
Client asked for an analysis of school performance by examining standardized test scores, school size, school type, and budget. Client also noted that the 9th grade scores of Thomas High School were suspected of academic dishonestly and requested that they be removed. The majority of the questions from this challenge involve how this effects the results.
## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.10 (64-bit), Jupyter Notebook 6.4.8

## Results

- How is the district summary affected?
  
  All grade percentage metrics were slightly decreased due to the removal of the 9th grade Thomas High School scores.
  
  **Before:**
  
  <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/district_summary_before.png" width="1000" />
 
  **After:**
  
  <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/district_summary_after.png" width="1000" />
  
- How is the school summary affected?
  
  All grade percentage metrics were slightly decreased due to the removal of the 9th grade Thomas High School scores. The other schools were uneffected.
  
  **Before:**
  
  <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/school_summary_before.png" width="1000" />
 
  **After:**
  
  <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/school_summary_after.png" width="1000" />
  
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  While a decrease was observed in the Thomas High School metrics, it was not a great enough decrease to change the rankings.
  
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grades
      
    These graphs are only effected by replacing the 9th grade Thomas High School grades with nan. The remaining cells were not effected by the removal.
  
  - Scores by school spending
      
    Any changes in these metrics were small enough that they rounded to the same number.
  
    **Before:**
  
    <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/budget_score_before.png" width="1000" />
 
    **After:**
  
    <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/budget_score_after.png" width="1000" />
  
  - Scores by school size
      
    Any changes in these metrics were small enough that they rounded to the same number.
  
    **Before:**
  
    <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/size_score_before.png" width="1000" />
 
    **After:**
  
    <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/size_score_after.png" width="1000" />
  
  - Scores by school type
      
    Any changes in these metrics were small enough that they rounded to the same number.
  
    **Before:**
  
    <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/type_score_before.png" width="1000" />
 
    **After:**
  
    <img src="https://github.com/justinkirk8/School_District_Analysis/blob/main/Resources/type_score_after.png" width="1000" />

## Summary
Overall, the removal of the 9th Grade Thomas High School had very little effect on the data. Slight decreases were observed in the overall metrics and the Thomas High School metrics; however, these decreases were not large enough to effect the graphs that examine the data by various classes. Slight decreases may have been observed in these graphs if the client had asked for higher significant figures in these particular area. 


