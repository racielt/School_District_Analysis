# School_District_Analysis

## Overview of the school district analysis: 

The purpose of this analysis is to get the affectation that the district metrics suffer with the 
modification on the Thomas High School grades (9th grade.).

Originally, we get the metrics of the school district, and of each school that is part of it.

We calculated the budget per district, per school and student. Also, we got the number of students, schools, the average math and reading scores, the percentage of students who passed math and reading, the overall passing percentage.

All this information helps the district determine the budget per school, so as soon as we modified the information of the Thomas High School, we must run the analysis again to see if there was a change on the results that will impact in the decision of the budget per school.

## Results:

  o	How is the district summary affected?
  
  <img width="929" alt="Screen Shot 2021-10-17 at 1 03 20" src="https://user-images.githubusercontent.com/90534703/137613966-defa0307-bbfb-40b7-a89f-359602a362eb.png">
  
  - In overall the numbers were not affected, the biggest change was in the overall passing percentage, it drops from 65.17% to 64.85%, if we round it, it is the same overall passing percentage, 65%

o	How is the school summary affected?
  
  - Regarding the THS results, we got the same results, not a significant change, in overall passing percentage, it drops from 90.95% to 90.63%, a 0.32% drop.

o	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  - As the numbers of THS didn’t suffer a big change, it is not an important affectation related with the other schools.

o	How does replacing the ninth-grade scores affect the following:

<img width="449" alt="THS NaN" src="https://user-images.githubusercontent.com/90534703/137614010-34e01faa-118c-4654-9219-8f3507b21532.png">


 - Math and reading scores by grade

Regarding the math and reading scores, the math average score went from 83.42 to an 83.35, but the only data that had an increment was the average reading score, it went form an 83.85 to a 83.90.

 - Scores by school spending

The group that was affected was the $630-644, but as the other affectation, it was not a big one. Overall, it went from 62.86% to 62.78%.

<img width="852" alt="Spanding_ranges" src="https://user-images.githubusercontent.com/90534703/137614049-018d3dd4-d3fc-4675-b6f3-11fe79e42b82.png">



 - Scores by school size

The school size affected was the medium size, because it was the group were THS is located, but the change is not a representative one.

 - Scores by school type

Finally, the school type that was modified, was the charter one, but only in a small percentage.

<img width="737" alt="charter" src="https://user-images.githubusercontent.com/90534703/137614064-8562aa63-a892-439b-ae51-43b62c52c9c5.png">


## Summary: 

Even though we take out a complete grade of one school, the overall numbers were not affected in a significant scale.

The affectation in the overall score was only of .32%, and it affected in the $630-644 spending range (only .08%), as you can see it is not an important change in the numbers, the same happen with the affectation that the charter category and the medium size group had, it is not a representative change.

These changes can only be noticed if we get more decimals, but if we take the nearest whole number, the difference cannot be appreciated.

In the PyCitySchools_Challenge is included the original analysis and the new one, so the affectation can be identified.
