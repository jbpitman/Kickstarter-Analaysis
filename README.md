# Kickstarting with Excel

## Overview of Project
Our client, Louise fell short of reaching her funding goal to raise money for her play *Fever*.  She would like to better understand successful campaigns.
Using the Kickstarter dataset, I examined the outcomes of the theatre campaigns (successful, failed and cancelled) and the month those campaigns were launched. 
I also examined the successful play projects and the goal amount. 

The Kickstarter data file includes data for a variety of funding campaign projects that were launched between 2010 and 2017.This project examines campaign launch and end dates; the goal amounts and actual amount raised for theatre and play projects. 
Visualizations (tables and graphs) were developed for Louise to show shows campaign outcomes (successful, failed, and cancelled).  Another visualization was developed the show outcomes and funding range amounts.
### Analysis of Outcomes Based on Launch Date
This analysis examines a total of 1, 369 theater projects which compromise approximately 34% of all projects included in the dataset. 
A total of 839 theatre projects were successful in meeting or exceeding their goal amounts (Outcome = *Successful*) and
 93 theatre projects failed to meet goals (Outcome=*failed*) and
 27 theatre projects were cancelled (Outcome = *canceled*) 
May showed the most successful play projects (111), followed by June when 100 successful play projects were launched. 

December had the fewest number of successful play projects (37). 
The following visualizations summarize the outcomes by launch month. 

! [This is a Summary of Outcomes by Campaign Launch Month] (https://github.com/jbpitman/Kickstarter-Analaysis/blob/main/Outcomes%20by%20Month.png)

! [This is a Summary of Outcomes by Campaign Launch Month] (https://github.com/jbpitman/Kickstarter-Analaysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Plays are a subcategory of theatre projects. The amount raised for plays accounts for ~ 61% of the total amount raised for
all theatre projects (~ $5 million) were for theatre projects which raised (~ $3.1 million).  Overall, most (73%) successful project have a goal of 
between $1,000 and $4,999.  Fifty-four (54%) of successful play projects had a goal between $10,000 and 14,999. 
One-half (50%) of the projects with a goal between $5,000 and $9,999 were successful. 
Interestingly, the same percentage (50%) failed projects had a goal within the 5,000 to 9,999 range. 

! [This is a Summary of Outcomes by Goal Amount] (https://github.com/jbpitman/Kickstarter-Analaysis/blob/main/Theater%20Outcomes_vs_Goal%20Amounts.png)

### Challenges and Difficulties Encountered
In drilling down on the data, it is very easy to mishandle the data which can lead to inaccurate conclusions. Mishandling includes sorting and filtering incorrectly which can lead to 
incorrect and inaccurate visualizations. For example, failing to apply filters for outcome or country would reveal different results.  Thankfully, this was avoided since the graphs
 were provided in the coursework. In real life, special care must be taken to review
the data and visualization. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	Based on this data, May and June are good months for launching successful play projects; however, the largest number of failed projects also occurred during these months. 
	December is not a good month for launching a theater funding campaign.   

- What can you conclude about the Outcomes based on Goals?
 If Louise is interested in launching a campaign for a play, based on the data analyzed a goal less than $10,000 increases her chance of meeting her goal.  
Amounts between $1,000 and $4,999 enjoyed the most success, followed by between 10,000 and 14,999  

- What are some limitations of this dataset?
This data reflects project launched between the years of 2010 and 2017. If Louise is asking for conclusions based on this data, the information may be no longer relevant due to its age.  
More recent data should be obtained in order to draw relevant conclusions that could be applied to future funding campaigns.


- What are some other possible tables and/or graphs that we could create?

Outcomes and duration of campaign: A line graph should be created to show outcomes (successful, failed, canceled) vs. duration of campaign (number of days campaigned)
Outcomes and total number of total campaigns: Bar graph to show number of all campaigns vs number of play and theater campaigns occurring at the same time? 
