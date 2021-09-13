# School District Analysis

## Overview of the School District Analysis

Following our initial analysis of the provided data for school districts, it was then discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect, updated data summaries were requested by the school board. After further discussion, it was best to only replace the ninth grade math and reading scores at Thomas High School with NaNs while keeping all other data associated with this student group intact. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. Once these math and reading scores are identified and replaced, the school board would like us to repeat the school district analysis previously performed in this module and write up a report to describe how these changes affected the overall analysis.

After updating our code, the initial data was updated following the below format omitting Thomas High School's ninth grade student scores.

![](Resources/NaN%20Update.PNG)

## Results

After making the updates mentioned above in regards to the Thomas High School math and reading scores, we ran an updated District Summary and School Summary in order to see how these changes affected the overall results of the seven school district metrics. 

### District Summary

 - The total number of students remained the same at 39,170 total students in the data set. 
 - The total budget also remained the same at $24,649,428 after the changes. 
 - The average math score decreased from 79.0 to 78.9 after the changes.
 - The average reading score remained the same at 81.9 after the changes.
 - The passing math percentage went down from 75% to 74.8% after the changes.
 - The passing reading percentage went from 86% to 85.7% after the changes.
 - The overall passing percentage dropped slightly after the changes from 65% to 64.9%.   

![](Resources/District%20Summary%202.PNG)

### School Summary

During our initial analysis, the Thomas High School had the second best overall passing percentage out of all the schools. Following our adjustment of the 9th grade scores, the Thomas High School kept its spot as the second best overall passing percentage out of all the school. 

 - The total of students, school budget and per student budget remained the same. 
 - The average math score decreased from 83.41 to 83.35 after the changes.
 - The average reading score increased from 83.84 to 83.89 after the changes.
 - The passing math percentage went down from 93.27% to 66.91% after the changes.
 - The passing reading percentage went down from 97.30% to 69.66% after the changes.
 - The overall passing percentage dropped after the changes from 90.94% to 65.07%. 

![](Resources/School%20Summary%203.PNG)

As we can see from the image above, replacing the ninth graders’ math and reading scores negatively affects Thomas High School’s performance relative to the other schools. The passing percentages have dropped significantly. 

### Math and reading scores by grade

![](Resources/Math%20Scores%20by%20Grade.PNG) ![](Resources/Reading%20Scores%20by%20Grade.PNG)

We see that the scores are replaced by NaNs therefore not included in the school's average scores. 

### Scores by school spending

![](Resources/Scores%20by%20school%20spending.PNG)

We see that the ranges are different and a bucket is created for nan transactions. 

### Scores by school size

![](Resources/Scores%20by%20school%20size.PNG)

The numbers are slightly impacted by the adjustment.

### Scores by school type

![](Resources/Scores%20by%20school%20type.PNG)

The numbers are slightly impacted by the adjustment.

## Summary

Upon review of the above mentioned results once the reading and math scores have been replaced, we see that the school's passing percentages were very much impacted by this adjustment. The results of the scores by school spending can be described as a change in the updated analysis. Thomas High School lost its placement as a top five school within this District. Lastly, there are no averages for this school's 9th grade results. 
