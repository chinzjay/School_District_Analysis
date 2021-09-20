# School_District_Analysis

## Overview
The purpose of this analysis is to analyze the school district data after replacing the scores of ninth graders at Thomas High School with NaNs as the scores seem to have been altered and to analyze how these changes affected the overall analysis. 

## Results
Using Pandas loc method with conditional statements, comparison and logical operators, the ninth-grade reading and math scores for Thomas High School were selected. A total of 461 scores were selected using the above criteria and their math and reading scores were changed to NaNs using the Pandas NumPy module. Since the selected scores were changed to NaN, the new passing percentages were calculated using the new student count which was obtained by subtracting the selected student count(461) from the original student count(39170).
- **District Summary Analysis** 

 *Fig 1*  depicts the district summary dataframe without making any changes to the reading and math scores of ninth graders at Thomas High School. * *Fig 2*  depicts the district summary Dataframe after making changes to the reading and math scores 
![district_summ_bfr](https://github.com/chinzjay/School_District_Analysis/blob/main/district_summ_bfr.PNG)
|:--:|
|Fig 1. District Summary before changing the scores|

![district_summ_aftr](https://github.com/chinzjay/School_District_Analysis/blob/main/district_summ_aftr.PNG)
|:--:|
|Fig 2. District Summary after changing the scores of Thomas High School ninth graders|

The following changes were observed in the school district metrics.
  * Average Math Score has reduced by 0.1.
  * Average Reading Score remains the same.
  * The percentage of students passing math has reduced by 0.2%.
  * The percentage of students passing reading has reduced by 0.3%.
  * The overall passing percentage has reduced by 0.1%.

- **School Summary**

*Fig 3*  depicts the school summary dataframe without making any changes to the reading and math scores of ninth graders at Thomas High School. * *Fig 2*  depicts the school summary Dataframe after making changes to the reading and math scores. 

![per_school_bfr](https://github.com/chinzjay/School_District_Analysis/blob/main/per_school_bfr.PNG)
|:--:|
|Fig 3. School Summary before changing the scores|

![per_school_aftr](https://github.com/chinzjay/School_District_Analysis/blob/main/per_school_aftr.PNG)
|:--:|
|Fig 4. School summary after changing the scores of Thomas High School ninth graders|

- **Performance of Thomas High School relative to other schools**
Replacing the math and reading scores of ninth graders has not affected the postion of Thomas High School’s based on schol performance. In both the cases, Thomas High School scores the second position in the Top 5 Schools list.

- **Math and reading scores by grade**
No differece observed in the average math and reading  by grade.

- **Scores by school spending**
No difference observed in the scores by school spending.

- **Scores by school size**
No difference observed in the scores by school size.

- **Scores by school type**
No difference observed in the scores by school type.

## Summary
The following changes are observed to the school district analysis after the reading and math scores have been replaced.
  - Average Math Score has reduced by 0.1.
  - The percentage of students passing math has reduced by 0.2%.
  - The percentage of students passing reading has reduced by 0.3%.
  - The overall passing percentage has reduced by 0.1%.
We can see that the average math score, passing math percentage, passing reading percentage and the overall passing percentage has reduced.
