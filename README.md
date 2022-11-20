# Pewlett-Hackard-Analysis

## Overview of Pewlett-Hackard-Analysis

### Purpose of Pewlett-Hackard-Analysis

#### The purpose of this project would be to help our manager in new tasks, after knowing how to control SQL in a slightly more advanced way. The task would be to find the number of employees who would be retiring in the following months from the company and categorize them based on their last title. Also, identify which employees could participate in the mentoring program to work part-time to help younger employees fit into their roles. Finally, write a report that summarizes and analyzes what has been previously described.

## Pewlett-Hackard-Analysis Results

### During the analysis of the results, it was essential to have carried out an in-depth study of the table of workers close to their retirement, since if this had not been done, the mistake of studying several retirement cases for the same worker could have been made (since several of them passed for different roles during their maturation within the company). As can be seen in the following lines of code, having made a small change to only study the last position in which each worker was developed made this study something deeper and more truthful.

![1](https://github.com/jjgomezg17/Pewlett-Hackard-Analysis/blob/main/Resources/Images/1.png)

![2](https://github.com/jjgomezg17/Pewlett-Hackard-Analysis/blob/main/Resources/Images/2.png)

### It is also interesting to see how such long tables can be summarized when studying a single variable. For example, when studying how many workers of each title within the company retire, a complex table like the ones studied in the previous point is summarized to 7 positions. Making it clear which are the titles within the company that more staff will need to be hired promptly.

![3](https://github.com/jjgomezg17/Pewlett-Hackard-Analysis/blob/main/Resources/Images/3.png)

### In addition, it would have been interesting to study in depth the roles and the number of people in each one that must be hired. Well, if current workers and possible promotions or eliminations of roles are taken into account, the number of new people that the company must hire is much less in quantity. So if you compare this table with a seniority table to see promotions and a role relevance table to see which ones can be deleted, the company might actually see a number closer to what it needs for its workforce.

### Finally, regarding the mentoring program, it is key to consider that this analysis could greatly help the company, since it would prepare new employees or possible promotions for what their future role would be. However, by encouraging only part-time workers who are about to retire, they could be discouraged and perhaps discouraged from helping their "replacements" in what would be their role within the company.

## Pewlett-Hackard-Analysis Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

#### A total of 72458 would be the number of roles that the "silver tsunami" would leave the company to find. However, this does not necessarily mean that the company has to find these workers in one fell swoop, since there will be many who wish to continue working after their retirement date or there will be those who have a different date planned. However, ultimately the company should be preparing to replace these roles in a period of about three years. Perhaps estimating for previous periods of retirement a percentage of the extent and speed of your pending retirement workers retire. Estimating 50% of these in the first year, 30% in the second and 20% in the third, just as an example. However, this would be clearer if the date of birth in the search was adjusted to be that of a particular year, the one that is soonest to retire.

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

#### Taking into account the factors that were decided to make the workers indicated for the mentoring program, it could be said that there are not enough employees to mentor the future workers of the company, since there are 1,550 workers who have the factors described. and there are 72,458 new roles for those who are leaving and a replacement must be found. However, this can be debated as there will be many roles that will be filled by experienced people who were just waiting for promotion or there will be roles that are no longer needed or perhaps one person could train 15 people each year for the next 3 years to make up the difference in population size or there may be many more people who qualify to be mentors by then.

### Additional queries or tables that may provide more insight into the upcoming "silver tsunami"

#### Continuing with the ideas previously described, for example, the employees only born in 1952 and who would be retiring this year would be 16,981 as shown in the following table, which would give HR a more tangible idea of those employees close to their retirement and of which a replacement or promotion must be found to occupy his position. Definitely a lower number and much closer to reality for at least the next year.

![4](https://github.com/jjgomezg17/Pewlett-Hackard-Analysis/blob/main/Resources/Images/4.png)

#### On the other hand, if workers who come from the upper limit of those who are going to retire to the upper limit of those previously studied are taken into account in the mentoring program, a little more than 186,000 possible mentors would be obtained who can who are willing to work their last years only part time and are willing to help future workers fit into their position, An offer of mentors that would cover more than double the demand for workers in the next 3 years, which means that many of them may be willing to be part of this program and perhaps at its best to have up to two mentors for each new worker. This can be seen in the "mentorship_eligibilty_1955_1965" table.
