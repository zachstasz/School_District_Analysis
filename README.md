# School District Analysis

## Overview of the school district analysis

Analyzing school district data, we gained insight to the relationship between the school spending, school size, school type, and the students' performance. However, due to academic dishonesty, the grades for Thomas High School's ninth graders have been called into question. We are to determine how omitting this data affects the results.

## Results

- When the data for Thomas High School's ninth graders is removed,
  - Average Math score went down from 79 to 78.9
  - Average Reading Score stayed the same at 81.9
  - % Passing Math went down from 75% to 74.8%
  - % Passing Reading down from 85.8% to 85.7%
  - Overall Passing went down from 65.2% to 64.9%

This is the original data
![Fig1](https://user-images.githubusercontent.com/103209236/168082765-53273863-3b02-465e-b2ca-3d88a67214a5.PNG)

This is the data with THS's ninth graders removed
![Fig2](https://user-images.githubusercontent.com/103209236/168082616-8c0fc056-a9e9-4f59-837d-c8dcb72fef1a.PNG)

- In the school summary, only Thomas High School was affected
  - Average Math score went down from 83.42 to 83.35
  - Average Reading Score went up from 83.85 to 83.9
  - % Passing Math went down from 93.27% to 93.19%
  - % Passing Reading down from 97.3% to 97.02%
  - Overall Passing went down from 90.95% to 90.63%

This is the original data
![Fig3](https://user-images.githubusercontent.com/103209236/168085660-fe6ae206-1157-43a1-bd3a-2a24dfbaf345.PNG)

This is the data with THS's ninth graders removed 
![Fig4](https://user-images.githubusercontent.com/103209236/168085671-b3df1c11-ef55-4bba-8ff1-6a8fd15df20e.PNG)

- Replacing the ninth graders’ math and reading scores did not affect Thomas High School’s performance relative to the other schools. They were still the second-best school.

This is the original data
![Fig5](https://user-images.githubusercontent.com/103209236/168086454-292ee5ef-3c45-4c56-b62a-9b03b9223493.PNG)

This is the data with THS's ninth graders removed 
![Fig6](https://user-images.githubusercontent.com/103209236/168086462-3112a7b2-7b8e-4a32-b79b-eba9d617c0be.PNG)

## Data
By replacing the 9th grade scores the following is affected:
  - The average math score for 9th graders goes down from 80.35 to 80.12
  - The average reading score for 9th graders goes down from 82.51 to 82.43
  - THS falls into the $631-645 range. The % Passing Reading went down from 84.4% to 84.3% and the % Overall Passing went down from 62.9% to 62.8%
  - THS falls into the Medium School range (1000-1999). The % Passing Reading went down from 96.8% to 96.7%
  - THS is a Charter School. The values were not affected.

## Summary
After replacing Thomas High School's 9th grade math and reading scores with NaNs, several changes occurred.
  - The overall passing % of THS went down
  - The average score for all 9th graders went down
  - The overall passing % of schools with 1,000-1,999 students went down
  - The overall passing % of schools that spent $631-645 per student went down
