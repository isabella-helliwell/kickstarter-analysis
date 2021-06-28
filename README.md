# 1. Kickstarter Analysis
##   1.1 Overview and purpose of the project

       Analysis are made to the kickstarter data to recognize and visualize any trends between the success rate 
       and that of funding goals and launch date specificaly for the theater category and plays. 
       The outcome of the analysis is shown in graphs.
       
# 2. Analysis and Challenges
       The analysis is performed in 2 parts.
       
       Part 1 is to visualize any link between launch date and outcome for the theater category.
       Part 2 is to visualize any link between funding goals and outcome for theater and subcategory plays.
      
       The main challenge with this project is to sort and plot data in such way that we get a meaningful overview of
       the outcomes.
       
         
##   2.1 Analysis of outcome based on Launch date
       The analysis carried out consists of looking to see if there is a link between successful funding goals and launch date.
       For this task, a data table is created counting the successful outcomes, failed outcomse and canceled outcomes
       for each month,and for all the years. The results are ploted in _Graph1.
       
       
 #### Graph1: Theater Outcomes Based on Launch Date      
![image](https://user-images.githubusercontent.com/85843030/123470156-00e03f00-d5c2-11eb-9565-8d022e413679.png)
       
       As shown in Graph1, the most successful month range to launch theater is between April and August, with May having the most 
       successful theater launches.
       The data also show the launch success rate decrease towards the end of the year, with December having the least 
       successful outcome.

##     2.2 Analysis of outcome based on funding goals
       For this analysis, some predefined funding goal ranges are used to decide if one funding goal range performs better
       than any other one, or if there is a trend between the funding goals and success rate. 
       The results are shown in Graph2
       
#### Graph2: Outcome based on funding goals for subcategory Plays
![image](https://user-images.githubusercontent.com/85843030/123492745-60514580-d5e8-11eb-9585-e0c8a30f0413.png)
       
       As shown in Graph2, the highest successrate is in the region of $0-$4999. After this region the successrate starts to 
       decrease and than picks up again between the regions of $25000 -$44999, and drops to 0 and increase again slightly.
       There are also no cancelation in the play category, as seen in Graph2.
       
# 3.Results       
##  3.1 Outcome based on launch date-results
        From Graph1, two conclusions can be made:
        * Highest success rate for theater is in May.
        * Highest fail rate for theater is in May as well.
        
        
##  3.2 Outcome based on funding goal-results
        From Graph2, the following  two conclusion can be made:
        * Highest successrate for funding goals happen for the $0-$4999 range.
        * There are no cancellations 
      
 # 4. Limitations of Datasets
##   4.1 Outcome based on launchdate-limitations

        Some Limitations:
        * In order to get a better understanding we can look into the outcome proportions for each month,see Graph 3.
        * We can see if this trend is the same if we isolate a country we are interested in launching our theatre in,
          see Graph 4 and Graph 5 for some examples.
        * We can also see if there is a genre that is more popular in the theater category
        * We can see how the theater category compares to the rest of the categories.


 ##   4.2 Outcome based on goals-limitations
       
        Some Limitations:
        * The graph does not show proportion of outcome vs total project for each month. It can be useful to see the total project
          for each defined goal range, see Graph 6.    
        * It can be useful to look closer to the goal ranges wehre success rate is higher and find out if there is any links to other
          parameters, see Graph 7 for a plot for funding goal in the range of $0-$20000
        * The graph does not limit our findings to any specific country. Different countries might have different trends.
        
            
 # 5. Additional Graphs   
       
       Shown below are some graphs that was discussed in the limitation chapters. Note that only a handful of additional graphs
       are shown below. One can create many more plots to answer more specific questions regarding the data sets provided in this
       task.
       
       
#### Graph 3       
![image](https://user-images.githubusercontent.com/85843030/123555234-7a0e9c00-d752-11eb-98fa-7effbdd43fba.png)

Comparing Graph 1  and Graph 3, it can be noted that the highest success rate still occurs for May month, however the percentage failed is lowest 
in the same month, while in Graph 1, the highest failed rate occured for May also.
       
 
 #### Graph 4
![image](https://user-images.githubusercontent.com/85843030/123556639-3ddf3980-d75a-11eb-9556-2ccf746bf415.png)

 
 #### Graph 5
 ![image](https://user-images.githubusercontent.com/85843030/123555550-711eca00-d754-11eb-8b5d-976082293e08.png)

Looking at Graphs 4 and 5 plots, the US and GB seem to have similar trends in terms og success rate in May. We
are able to say that since these two countries had the most total projects, they dominated the data set in Graph1.



#### Graph 6       
![image](https://user-images.githubusercontent.com/85843030/123556091-5ac63d80-d757-11eb-8803-30cc6cfd014f.png)


#### Graph 7
![image](https://user-images.githubusercontent.com/85843030/123556651-5fd8bc00-d75a-11eb-9de4-bdf963f963a1.png)

Graphs 6 and 7 show that there are more projects in the $0-$4999 goal range, that any other range. If we
take a closer look it can be seen that the overal percentage of success is higher for the $0-6000 range. Hence it seems that
it is easier to obtain a successful outcome when your goal range limit is in the $6000 range or less.



