# School_District_Analysis

## Overview

In this module, the *Python's Pandas* library is used to process and analyze standarized student's math and reading test results as well as school's funding data gathered from the school system of the city.

A first school distric analysis was conducted with the **[PyCitySchools](./Module/PyCitySchools.ipynb) jupyter notebook**. Even though it provided insights about the performance of the students and the schools in the city, later on, the school board was notified that there is evidence that the results of the 9th grade students from the Thomas High School were altered.

The school board then decided to invalidate the manipulated results from the **[student's input data](./Resources/students_complete.csv)**. This meant that those values need to be replaced and the school district analysis should be repeated.

With the **[PyCitySchools_Challenge](./PyCitySchools_Challenge.ipynb) jupyter notebook**, the Thomas High School, 9th grade results are invalidated and a new school district analysis is conducted. The repeated analysis will help the school board in making strategic decitions to improve the quality of the education system.

Three final deliverables are provided:

- The school district analysys report (This README.md file).
- The **[school district analysis jupyter notebook](./PyCitySchools_Challenge.ipynb)** to replace the invalid results.
- The **[school district analysis jupyter notebook](./PyCitySchools_Challenge.ipynb)** to repeat the school district analysis.

## Results

**1. How is the district summary affected?**

The district summary is a single row table containing information about the schools in the district being analyzed. In this case fifteen schools were analyzed and information such as the total number of students, the total budget destinated to the schools and the standarized math and reading testing results as well as passing statistics are displayed.

The Image 01, shows the school district summary tables for the data before (top) and after (below) the annulation of the math and reading scores of the 9th grade students from the Thomas High School.

![Image 01](./Resources/01_Distric_Summary.png)

*Image 01: School Distric Summary Tables*

As observed, there are some differences between both tables and a reduction of the average scores and passing percentages are expected due to the edition of the data, however this reduction is small as the data affected represent only a small sample of all the data averaged here.

**2. How is the school summary affected?**

The school summary is a table showing the information such as the number of students, the budget, the test results and the passing statistics of each school. Keeping in mind that the data edition only affected the Thomas High School, the differences between the tables shown in Images 02a and 02b are narrowed down to this Charter school.  

![Image 02a](./Resources/02a_School_Summary_Before.png)

*Image 02a: School Summary Table before data edition*

![Image 02b](./Resources/02b_School_Summary_After.png)

*Image 02b: School Summary Table after data edition*

**3. How does replacing the ninth graders’ math and reading scores affect Thomas High?**

**4. School’s performance relative to the other schools?**

**5. How does replacing the ninth-grade scores affect the following:**
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type

## Summary

<!-- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs -->

<!-- ![Image3](./Resources/Code_part02.png)

*Image 3: PyPoll Python 3 script, total number of votes and vote count by county & candidate* -->