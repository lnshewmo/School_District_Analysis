PyCity School District Analysis

# Purpose

For this project, were given 2 data sets: one containg student performance by grade by school and another containing budgets by school.  The objective was to aggregate the data and evaluate possible trends in student performance by spending, school size and school type. This analysis will help inform the school board as they prepare budgets for the following school year. 

After this initial analysis was completed, it was determined that the reading and math scores for 9th graders at Thomas High School (THS) were compromised and should be nullified.  Following this, the analysis was repeated.  The results below reflect calculations based on this revised data set.

# Resources

Data Sources : [schools_complete.csv](https://github.com/lnshewmo/School_District_Analysis/blob/main/Resources/schools_complete.csv), [students_complete.csv](https://github.com/lnshewmo/School_District_Analysis/blob/main/Resources/students_complete.csv)
Software: Python 3.9.12, JupyterLab

# Results

## District Summary

Initial District Summary

![district_summary](/Resources/district_summary.png)

Revised District Summary

![revised_summary](/Resources/district_summary_reanalysis.png)

Removing the figures from the THS 9th graders did not significantly impact the overall distric summary.  This is not surprising because there are only 461 9th graders at THS out of a total district population of 39,170 students.

## School Summary

The school summary was not affected by the compromised THS data.  The scores for all high schools aside from THS did not change.  

![school_summary](

Replacing the THS 9th grade scores with NaN pulled the remaining THS percentages down because the calculations were not accurately reflecting the whole student population at this point.  The analysis for THS would have to be performed outside this set on just the 10-12th grade students.

## Thomas High School Reanalysis



Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

# Summary

Changes in the analysis after THS 9th grade scores were removed.
1.
2.
3.
4.
