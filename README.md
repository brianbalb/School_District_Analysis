# School_District_Analysis

##As requested by client Maria for analyzing school district data to gather new insights and visually provided by clear results on individual school performance. 

## Analysis Purpose 
3 key purposes are as follows:
* Clean and prepare data to provide clear insight on individual school performance and budgets
* Uphold state-testing honesty: find academic dishonesty in school and ommiting such data from currupting analysis
* Conduct origianl analysis with update, ommiting Thomas High School data because of dishonesty, to figure out the impact the dishonesty had and accurate update district results.

# Requested Information Results: Using bulleted lists and images of DataFrames as support, address the following questions.

The dishonesty was found to have accured at Thomas High School within the 9th grade data. To follow the stat standards we have ommited all data from Thomas High School using Nan as place holder. Dataframes where created to display important information. 

## How is the district summary afftected?

* The overall passing percentage for Thomas High School fell to 65%
* The overall passing percentage for the entire district fell to 64.9%
* Thomas High School was no longer included on the list of top five schools.

How is the school summary affected?

* The overall passing percentages of Thomas High School decreased by 0.11%
* The average scores of Thomas High School for math and reading increased by 0.06
* For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* School rankings are unchanged
* Thomas High School is still the second best performing school in the district 
* Overall passing rate of 90.63% among their tenth through twelfth graders

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
### Scores by school spending

* Average Scores and Passing Percentages do not increase as spending per student increases. 
* The top performing school in the entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School)
* There are more relevant factors than funding that decide average student scores

## Scores by school size
### Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools

* Charter schools generally performed better than District schools
* The top five schools with the highest overall passing percentages are all Charter schools
* The bottom five are all District Schools 
* Ultimately Charter schools have a 36% higher overall passing percentage than District schools

## Scores by school type
### Analyzing the average scores for math and reading by grade level for each school

* Sttudents grade level does not affect their scores as much as the school that they attend
* The average scores within each school only varries by 1-2% depending on grade level
* The difference in scores is more apparent when comparing different schools

# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

## Relacing the ninth graders' scores with NaN caused 

* Thomas High School's overall passing percentages and average scores to plummet
* The district as a whole had its average math and reading scores decrease
* The overall passing percentage for students in the district decreases as a whole
* Thomas High School lost its placement as a top five school within this District

Ultimately, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. Unfortunately, it is not possible to conclude the extent of the damage and dishonesty from Thomas Highs School exclussion. However our analysis is the best insight we can get with the updated cleaned datasets. 
