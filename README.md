# PyPoll with Python

## Overview of the Project

### Purpose

The goal of the project is to help Maria, the chief data scientist for a city school district, analyze the performance of the schools within the particular district. This will be accomplished through the use of Pandas in the Jupyter Notebook environment. Tables containing the following metrics were requested:
•	Top 5 and bottom 5 performing schools, based on the overall passing rate.
•	The average math score received by students in each grade level at each school
•	School performance based on budget per student
•	School performance based on school size
•	School performance based on type of school

All of these were completed and submitted to the school board. They were appreciative of the exhaustive work and were happy to pour over the data. After doing so, they notified Maria and her supervisor that the file shows evidence of possible academic dishonesty by Thomas High School ninth graders in both the reading and math grades. It looks like the grades have been possibly altered. In order to uphold state-testing standards to the highest possible level it was requested that these scores be removed and replaced with NaNs. After this the analysis would be replicated to determine the effect the dishonesty had on the results.

## School Analysis Results and Comparison

### Results
The second analysis of the data took significant time to replicate, however, there was code from the original analysis that was able to be reused with slight alterations. Below are the contrasting figures of the results for Thomas High School in both the original and secondary analysis with the clean data.

Test Scores in Original Analysis
       ![This is and image](https://github.com/johnjphenom/week4_pandas_hw/blob/main/Resources/header.png)
![This is and image](https://github.com/johnjphenom/week4_pandas_hw/blob/main/Resources/thomas_summary_original.png)


Test Scores in Second Analysis
        ![This is and image](https://github.com/johnjphenom/week4_pandas_hw/blob/main/Resources/header.png)
![This is and image](https://github.com/johnjphenom/week4_pandas_hw/blob/main/Resources/thomas_summary_clean.png)


This clearly shows that there was an impact on the average math score, the average reading scores, the percent passing math, the percent passing reading, and the percentage of those that were passing overall. 

When looking at the overall district analysis we can see slight changes as well in most of the of the metrics measured as explained below.
*Total School Budget: There was not a change here as the school budget stayed static from one analysis to the next. 
*Per Student Budget: There was also not a change to this because the overall school budget stayed the same and the total number of students stayed the same as well. There was no impact when looking at the success of a school in a particular spending bin though. Thomas High School is in the $631 to $645 per student spending range and the % Overall Passing score stayed the same 63%.
* Average Math Score: When looking at these scores for Thomas High School we see the change by a decrease of .05 points.
* Average Reading Score: The reading scores for Thomas High School also dropped by about .05 points.
* % Passing Math: The percentage of students passing math from Thomas High School dropped by about .1 percentage points.
* % Passing Reading: The percentage of students passing reading from Thomas High School dropped by about .3 percentage points.
*% Overall Passing: The percentage of students passing overall for Thomas High School dropped by about .3 percentage points as well.

### Summary
After looking at the data in the subsequent analysis we can see that there was an impact on the scores and percentage rates of passing. These changes do appear to be quite small though. This is because out of the 1635 students at Thomas High School 1174 of them are 10th-12th graders. This lessens the overall impact of the removal of grades. As can be seen in the below image detailing the top 5 schools in the district, Thomas High School still places second in overall passing. 

Top 5 Schools
![This is and image](https://github.com/johnjphenom/week4_pandas_hw/blob/main/Resources/top_5.png)


As shown in the section above the removal of the grades of ninth graders at Thomas High School only had a very small change in Average Reading Score, Average Math Score, % Passing Reading, % Passing Math, and % Overall Passing. When looking at the district as a whole the change is not really there because the amount of 9th graders at Thomas High School is small compared to the overall amount of students in the district. 

