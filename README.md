# School_District_Analysis

## Overview
The purpose of this analysis is to analyse the school district data after replacing the scores of ninth graders at Thomas High School with NaNs as the scores seem to have been altered and to analyse how these changes affected the overall analysis. 

## Results
Using the Pandas loc method with conditional statements, comparison and logical operators, the ninth-grade reading and math scores for Thomas High School was selected. A total of 461 students was selected using the above criteria and their math and reading scores were changed to NaNs using the Pandas NumPy module. Since the scores of the above mentioned students were dropped, the new passing percentages were calculated using the new student count which was obtained after subtracting the selected student count(461) from the original student count(39170).

The following observations were made after changing the scores as mentioned above
- 

![district_summ_bfr](https://github.com/chinzjay/School_District_Analysis/blob/main/district_summ_bfr.PNG)
|:--:|
|Fig 1. District Summary before changing the student count|

![district_summ_aftr](https://github.com/chinzjay/School_District_Analysis/blob/main/district_summ_aftr.PNG)
|:--:|
|Fig 2. District Summary with the changed student count|

How is the school summary affected?
https://github.com/chinzjay/School_District_Analysis/blob/main/per_school_bfr.PNG
https://github.com/chinzjay/School_District_Analysis/blob/main/per_school_aftr.PNG
Replacng replacing the ninth graders’ math and reading scores has not affected the postion of Thomas High School’s based on schol performance. THS still is the top second schol after replacing the grades
We can see that there is no difference in the average math and reading scores by school size, school type or school spending after repalcing the ninth grade scores.

## Summary
: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced
