# School District Analysis

## Overview of the School District Analysis
 Following our initial analysis of the provided data for school districts, it was then discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect, updated data summaries were requested by the school board. After further discussion, it was best to only replace the ninth grade math and reading scores at Thomas High School with NaNs while keeping all other data associated with this student group intact. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. Once these math and reading scores are identified and replaced, the school board would like us to repeat the school district analysis previously performed in this module and write up a report to describe how these changes affected the overall analysis.

After updating our code, the initial data was updated following the below format omitting Thomas High School's ninth grade student scores.

![](Resources/NaN%20Update.PNG)

## Results
 After making the updates mentioned above in regards to the Thomas High School math and reading scores, we ran an updated District Summary in order to see how these changes affected the overall results of the seven school district metrics. 

 - The total number of students remained the same at 39,170 total students in the data set. 
 - The total budget also remained the same at $24,649,428 after the changes. 
 - The average math score decreased from 79.0 to 78.9 after the changes.
 - The average reading score remained the same at 81.9 after the changes.
 - The passing math percentage went down from 75% to 74.8% after the changes.
 - The passing reading percentage went from 86% to 85.7% after the changes.
 - The overall passing percentage dropped slightly after the changes from 65% to 64.9%.   

![](Resources/District%20Summary%202.PNG)

## Summary
 Upon review of the above mentioned results once the reading and math scores have been replaced, only the average math scores, passing math percentage, passing reading percentage and overall passing percentage were negatively impacted. This said, the adjusmtnents made do not heavily impact our initial results. The school board can uphold state-testing standards based on our updated analysis.
