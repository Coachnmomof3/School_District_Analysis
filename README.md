# School District Analysis

## Overview of the school district analysis:

The School board findings of a file showing evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The School board do not know the extent to the level of dishonesty, they want to uphold state-testing standards. Maria asked to assist her by replacing the math and reading scores for Thomas High School with NaNs from the rest of the data. I was also tasked with doing the school district analysis and providing a written report.

## Results:

### How is the district summary affected?
- ##### Before
![District_Summary_Before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/District_Summary_Before.png)
- ##### After
![District_Summary_After](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/District_Summary_After.png)

### District Summary Analysis

The district summary was not affected in the following columns: total schools, and total students. There were minimul changes to the Passing Reading Percentage(From 86% to 85%), Passing Math Percentage(From 75% to 74%), and Overall Passing Percentage(From 65% to 64%). Averages remained identical throughout my analysis. 

### How is the school summary affected?
- ##### Before
![School_Summary_Before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/School_Summary_Before.png)
- ##### After
![School_Summary_Before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/School_Summary_After.png)

### School Summary Analysis

The school summary was affected in a major way. In the school summary before and after data frames shown above we can see the overall passing percentage go from about 91% to 65% that is a significant difference from including the 9th graders and when they are no longer included. Thomas High School dropped significantly considering it was one of the best high school in the district based overall passing both math and reading. We see it dropped from being one of 15 Relative to other schools.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth graders' math and reading scores affected Thomas High School's performance compaired to the other schools. The data for the 9th graders at Thomas High school for all scores were removed and placed with a NaN value, putting them at the bottom of each list.



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


Thomas High School is apart of the $630-644 group in which we saw major decreases in many different aspects. We see the following categories decrease: Passing Math Percentage went from 73% to 67%, Passing Reading Percentage fromn 84% to 77%, and the Overall Passing Percentage from 63% to 56%. On the up side the averages did stay consistant.

#### Scores by school size

- ##### Before
![Scores by school size before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20size%20before.png)
- ##### After
![Scores by school size](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20size1.jpg)

With Thomas High School being considered a medium sized high school there was a significant decrease in the following categories: Passing Math Percentage 94% to 88%, Passing Reading Percentage 97% to 91%, and Overall Passing Percentage 91% to 85%. Averages stayed consistant for both reading and math.

#### Scores by school type

- ##### Before
![Scores by school type before](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20type%20before.png)
- ##### After
![Scores by school type](https://github.com/Coachnmomof3/School_District_Analysis/blob/master/Resources/Scores%20by%20school%20type1.jpg)

Thomas High School is identified as a Charter school. It experienced a significant decrease in the following categories: Passing Math Percentage from 94% to 90%, Passing Reading Percentage from 97% to 93%, and the Overall Passing Percentage from 90% to 87%. Our averages stayed consistant for both reading and math.

## Summary:

In my analysis by school size, school type and school spending groups the following categories showed the greatest variances when the 9th grade scores were removed for Thomas High School: Passing Math Percentage, Passing reading Percentage, and Overall Passing Percentage. Analysis from school summary showed Thomas High School relative to other schools when we removed the 9th graders it showed a significant decrease in their positioning from the top of the schools to mid range.
