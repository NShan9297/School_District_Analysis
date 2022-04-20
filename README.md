# School_District_Analysis #

# **Overview** #

For this project, Data Scientist Maria has asked for help with the analysis of a school district's standardized test scores. Student scores for math and reading were analyzed by school, school type (District or Charter), school size, and the budget for each school and spending per student. We are looking to see what affects, if any, that these variables have on test scores. This in turn will allow the School Board the opportunity to better budget for each school for each year.

During collection of the data, Maria was advised by the school board that there is an error. The 9th grade student scores from Thomas High School (THS) were either falsified or fabricated and she must remove these. We then look to see what affect, if any, that removing these scores from the data set will have on the overall scores and the scores for THS.

## Data Set ##

15 schools 

39,170 students math and reading scores (before removal)

38,709 students math and reading scores (after removal)


# Results #

# **District Summary** #
**How is the district summary affected?**

The District summary seems to display some slight changes in percentages but does not seem to be impacted in a major way:
insert old and new dats frame 

- We see an increase in the Overall passing percentage in the district:

    ***New Overall Passing Percentage***
  
    75.8738 % (math)
  
    86.8273 % (reading) 

    ***Old Overall Passing Percentage***
  
    74.9808 % (math)
  
    85.80546 % (reading) 


- We see a decrease in the number of students passing in the district as well

    ***New Number of Students Passing***
  
    28939(math)
  
    33158 (reading)
  

    ***Old Number of Students Passing***
  
    29370(math)
  
    33610 (reading) 
  

- We see a decrease in the overall passing percentage

    ***Overall passing percentage***

    Before: 65.1723%
  
    After: 64.85571%
  

# **School Summary** #
**How is the school summary affected?**

The school summary for this data set was affected tremendouly when broken down to a school level and presumably based on per grade percentages.  Overall, we still do not see a major shift one way or the other for the overall data after THS is removed. As no data was removed for any other school and the metrics did not call for percentages to be obtained at a grade level, all that is displayed is a "NaN" for THS 9th graders. I would expect that the reading average at the ninth grade level would increase due to the way the THS grades were impacted. 

# **Removal of 9th Graders at THS** #
THS saw the greatest and most tangible effects of the ninth grade data being removed from the data set

# **Removal of 9th Graders Overall Impact** #






