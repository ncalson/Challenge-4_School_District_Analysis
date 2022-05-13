# Module 4 | Assignment - PyCitySchools -- School District Analysis

Use Python and the Pandas library to analyze school district data and showcase trends in school performance.

## Overview
Due to concerns of dishonesty regarding math and reading scores at Thomas High School, Maria was asked to do the following:
- Replace the math and reading scores for Thomas High School with NaNs without changing the rest of the data
- Repeat the school district analysis and see how the analysis may have changed after making the above changes


## Results
### How is the district summary affected?
The district summary is minimally affected.
- Initial District Summary Results: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Old%20District%20Summary.png)
- Revised District Summary Results: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/New%20District%20Summary.png)


### How is the school summary affected?
After replacing the math and reading scores for Thomas High School, there's a minimal decrease to the overall passing test score column:
- Initial School Summary Results:

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Thomas%20High%20School_Old%20School%20Summary.png)

- Revised School Summary Results: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Thomas%20High%20School_New%20School%20Summary.png)


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth graders' math and reading scores does not greatly affect Thomas High School's ranking among other schools as it remains at second place within the top five schools.


### How does replacing the ninth-grade scores affect the following:
#### - Math and reading scores by grade: 
Math and reading scores now show "nan" for the ninth grade column
- Math:

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Math%20Scores_nan.png)

- Reading: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Reading%20Scores_nan.png)


#### - Scores by school spending: 
The spending range of $630-644 sees a 1% decrease (84% decreased to 83%) in the "% Passing Reading" column.
- Original: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Scores%20by%20School%20Spending_orig.png)

- Revised: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Scores%20by%20School%20Spending.png)


#### - Scores by school size: 
The scores by school size section is generally unaffected.
- Original: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Scores%20by%20School%20Size_orig.png)

- Revised:

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Scores%20by%20School%20Spending.png)


#### - Scores by school type: 
The scores by school size section is generally unaffected.
- Original: 

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Scores%20by%20School%20Type_orig.png)

- Revised:

![this is an image](https://github.com/ncalson/Challenge-4_School_District_Analysis/blob/main/Scores%20by%20School%20Type.png)


## Summary
Generally the data did not drastically change after reconducting the analysis. Below are the four main impacts:
1. Generally grades and percentages were decreased for Thomas High School.
2. "% Passing Reading" was impacted in the "Scores by School Spending" table as there was a 1% decrease on the $630-644 line in this column.
3. Scores by school size and school type were not noticeably impacted.
4. "NaN" results for Thomas High School in the ninth grade math and reading scores were now being included in the data.
