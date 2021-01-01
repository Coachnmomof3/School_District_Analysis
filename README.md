# School District Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

The School board findings of a file showing evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The School board do not know the extent to the level of dishonesty, they want to uphold state-testing standards. Maria asked me to assist her by replacing the math and reading scores for Thomas High School with NaNs from the rest of the data. I was also tasked with doing the school district analysis and providing a written report.

## Results:

### How is the district summary affected?
- ##### Before
![District_Summary_Before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/District_Summary_Before.png)
- ##### After
![District_Summary_After](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/District_Summary_After.png)

### District Summary Analysis

The district summary was not affected in the columns Total schools, and total students.
Passing Reading Percentage(From 86% to 85%), Passing Math Percentage(From 75% to 74%), and Overall Passing Percentage(From 65% to 64%). The averages remained intrechangable throughout my analysis. 

### How is the school summary affected?
- ##### Before
![School_Summary_Before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/School_Summary_Before.png)
- ##### After
![School_Summary_Before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/School_Summary_After.png)

### - School Summary Analysis
The school summary had a major affect, from the School summary before and after data frames above we can see that there is a significant difference from when freshman were included and when they are not being included. Our overall passing percentage goes from about 91% to 65%. Relative to other schools, Thomas High School dropped significantly considering it was one of the best high school in the district based overall passing both math and reading. Now it had dropped being one of 15 other schools.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth graders' math and reading scores affected Thomas High School's performance to the other schools. The data for the freshman at Thomas High school for all scores were removed and placed with a NaN value, putting them at the bottom of each list.

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade

- ##### Before
![Math and reading scores by grade before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Math%20and%20Reading%20scores%20by%20grade%20before.png)
- ##### After
![Math and reading scores by grade](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Math%20scores%20by%20grade.png)

The data for the freshman at Thomas High school for both reading and math scores were removed and placed with a NaN value, putting them at the bottom of each list.

#### Scores by school spending

- ##### Before
![Scores by school spending before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20spending%20before.png)
- ##### After
![Scores by school spending](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20spending1.jpg)


To start, Thomas High School was apart of the $630-644 group in which we saw major decreases in many different aspects. To start, we see the following categories decrease: Passing Math Percentage (From 73% to 67%), Passing Reading Percentage (Fromn 84% to 77%), Overall Passing Percentage(From 63% to 56%). On the other hand our averages did stay constant.

#### Scores by school size

- ##### Before
![Scores by school size before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20size%20before.png)
- ##### After
![Scores by school size](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20size.png)

Thomas High School is a Medium sized high school again saw a significant decrease in the following categories: Passing Math Percentage(From 94% to 88%), Passing Reading Percentage(From 97% to 91%), and Overall Passing Percentage(From 91% to 85%). Our averages stayed constant for both reading and math.

#### Scores by school type
- ##### Before
![Scores by school type before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20type%20before.png)
- ##### After
![Scores by school type](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20type.png)

Thomas High School is a Charter high school and saw a significant decrease in the following categories: Passing Math Percentage(From 94% to 90%), Passing Reading Percentage(From 97% to 93%), and Overall Passing Percentage(From 90% to 87%). Our averages stayed constant for both reading and math.

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

In conclusion, with the by school size, type and school spending groups the following categories had the biggest changes when we removed the freshman scores for Thomas High School: Passing Math Percentage, Passing reading Percentage, and Overall Passing Percentage. Our School Summary showed Thomas High School relative to other schools when we removed the freshman which showed the significant decrease in their positioning from the top of the schools to mid table.
