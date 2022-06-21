# PyCity School District Analysis

## Purpose

For this project, were given 2 data sets: one containg student performance by grade by school and another containing budgets by school.  The objective was to aggregate the data and evaluate possible trends in student performance by spending, school size and school type. This analysis will help inform the school board as they prepare budgets for the following school year. 

After this initial analysis was completed, it was determined that the reading and math scores for 9th graders at Thomas High School (THS) were compromised and should be nullified.  Following this, the analysis was repeated.  The results below reflect calculations based on this revised data set.

## Resources

- Data Sources : [schools_complete.csv](https://github.com/lnshewmo/School_District_Analysis/blob/main/Resources/schools_complete.csv), [students_complete.csv](https://github.com/lnshewmo/School_District_Analysis/blob/main/Resources/students_complete.csv)
- Software: Python 3.9.12, JupyterLab

## Results

The completed script for the analysis is available **[here](https://github.com/lnshewmo/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb).**

### District Summary

Initial District Summary

![district_summary](/Resources/district_summary.png)

Revised District Summary

![revised_summary](/Resources/district_summary_reanalysis.png)

Removing the figures from the THS 9th graders did not significantly impact the overall district summary.  
This is not surprising because there are only 461 9th graders at THS out of a total district population of 39,170 students.

### School Summary

The school summary did not change with the exception of THS percentages.

This table shows the school summary before the 9th grade THS data was removed.

![school_summary](Resources/school_summary.png)

Replacing the THS 9th grade scores with NaN pulled the passing percentages down because the calculations were not accurately reflecting the whole student population at this point.  The analysis for THS would have to be performed outside this set on just the 10-12th grade students.  This entry shows THS passing percentages after the 9th grade scores were replaced with NaNs. 

![THS_summary](Resources/school_summary_reanalysis.png)

### Thomas High School Reanalysis

To correct the school summary table for THS passing percentages, new calculations were completed based on only the remaining 1174 10-12th grade students.  The new passing percentages were added back to the school summary table using `.loc` statements.  This table shows the complete school summary after revision of the THS percentages.

![revised_school_summary](Resources/revised_school_summary.png)

Math Scores by Grade

!

Reading Scores by Grade

!

Scores by School Spending

!

Scores by School Size

!

Scores by School Type

!


## Summary

Changes in the analysis after THS 9th grade scores were removed.
1.
2.
3.
4.
