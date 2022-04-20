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

                                             **original district summary**
                     
![Old_Dist_Sum](https://user-images.githubusercontent.com/99927324/164128480-e6266b59-af2b-4063-8d73-6937dd9bcdd1.png)
                                                
                                                **and new below**

![Dist_Sum](https://user-images.githubusercontent.com/99927324/164128555-670ffb54-d11c-4036-991e-05be9af0f17b.png)

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
THS saw the greatest and most tangible effects of the ninth grade data being removed from the data set. The THS average for both math and reading was originally in the 60s, after removal, the scores shot up to over 90% for both math and reading:


                                            **Thomas High School before**
![THS_before](https://user-images.githubusercontent.com/99927324/164128855-4cbf543d-b8ac-4367-ab93-3821d50a9586.png)



          `                                 **Thomas High School after***
![THS_after](https://user-images.githubusercontent.com/99927324/164128949-d408a1af-4f20-4c9d-b209-f6276ae60043.png)




# **Removal of 9th Graders Overall Impact** #

- Math and reading scores by grade
  we don't see any changes in the scores by grade as the percentages were not calulated which would have shone more light on how much the average was being pulled down   THS 9th grade students

- Scores by school spending

- Scores by school size
The bins used to gather the school data were 

size_bins = [0, 999, 1999, 5000]

group_names = ["Small (<1000)", "Medium (1000-1999)", "Large (2000-5000)"]

And the budget was not an adjustable variable, the budget remained the same, furthermore, as THS started as a "Medium Sized School" at 1635 students. When the 461 students were removed, it left a student population of 1174 which, based on the above, is still considered a medium size school 

- Scores by school type




# **Summary** #
