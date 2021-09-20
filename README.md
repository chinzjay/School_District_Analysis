# School_District_Analysis

## Overview
The purpose of this analysis is to analyze the school district data after replacing the scores of ninth graders at Thomas High School with NaNs as the scores seems to be altered and to analyze how these changes affected the overall analysis. 

## Results
Using Pandas loc method with conditional statements, comparison and logical operators, the ninth-grade reading and math scores for Thomas High School were selected. A total of 461 scores were selected using the above criteria and their math and reading scores were changed to NaNs using the Pandas NumPy module. Since the scores were replaced, the new passing percentages were calculated using the new student count which was obtained by subtracting the selected student count(461) from the original student count(39170).
1. **District Summary Analysis** 

*Fig 1*  depicts the district summary Dataframe without making any changes to the reading and math scores of ninth graders at Thomas High School. *Fig 2*  depicts the summary Dataframe after the scores were replaced. 
 
![district_summ_bfr](https://github.com/chinzjay/School_District_Analysis/blob/main/district_summ_bfr.PNG)
|:--:|
|Fig 1. District Summary before changing the scores|

![district_summ_aftr](https://github.com/chinzjay/School_District_Analysis/blob/main/district_summ_aftr.PNG)
|:--:|
|Fig 2. District Summary after changing the scores|

The following changes were observed in the school district metrics.
  - Average Math Score has reduced by 0.1.
  - Average Reading Score remains the same.
  - The percentage of students passing math has reduced by 0.2%.
  - The percentage of students passing reading has reduced by 0.3%.
  - The overall passing percentage has reduced by 0.1%.

   
2. **School Summary**

*Fig 3*  depicts the school summary Dataframe before replacing the scores. *Fig 4*  depicts the school summary Dataframe after replacing the reading and math scores. 

![per_school_bfr1](https://github.com/chinzjay/School_District_Analysis/blob/main/per_school_bfr1.PNG)
|:--:|
|Fig 3. School Summary before changing the scores|

![per_school_aftr1](https://github.com/chinzjay/School_District_Analysis/blob/main/per_school_aftr1.PNG)
|:--:|
|Fig 4. School summary after changing the scores|

The following changes were observed in the school summary of Thomas High School.
  - The percentage of students passing math has reduced significantly from 93.2% to 66.91%
  - The percentage of students passing reading has dropped to 69.7% from 97.1%.
  - The overall passing percentage has reduced to 65.1% from 90.6%.

3. **Performance of Thomas High School relative to other schools**

Replacing the math and reading scores of ninth graders of Thomas High School has not affected the performance of Thomas High School relative to other schools. In both the cases, Thomas High School scores the second position in the Top 5 Schools list.

4. **Math and reading scores by grade**

No differece observed in the average math and reading by grade.

5. **Scores by school spending**

No difference observed in the scores by school spending.

6. **Scores by school size**

No difference observed in the scores by school size.

7. **Scores by school type**

No difference observed in the scores by school type.

## Summary
The following changes were observed to the school district analysis after the reading and math scores has been replaced.
  - Average Math Score has reduced by 0.1.
  - The percentage of students passing math has reduced by 0.2%.
  - The percentage of students passing reading has reduced by 0.3%.
  - The overall passing percentage has reduced by 0.1%.
  
We can infer from the above analysis that the average math score, passing math percentage, passing reading percentage and the overall passing percentage has reduced after replacing the scores.
Analysing the school summary Dataframe, we can infer that the passing math percentage, passing reading percentage and overall passing percentage has reduced significantly after replacing the scores.
