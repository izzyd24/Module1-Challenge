# Module1-Challenge
* Please note, I have submitted the file 'Challenge 1 Sheet' in order to only include the two deliverables
* If you would like to see the sheet I did all my class work on, please ask!
## Overview of Project
* Louise Fever play w/ fundraising goal fell short due to time 
* Wants to know how different campaigns did in relation to: 
*   1. Launch dates
*   2. Funding goals
* Use Kickstarter dataset 
* Outcome: using the kickstarter data, was able to generate outcomes based on goals (line graph) and use pivot tables to show start date data for the category of 'theater'. 

### Analysis of Outcomes Based on Launch Date
- Two conclusions about the Outcomes based on Launch Date: 
![Theater Outcomes_Vs_Launch](https://user-images.githubusercontent.com/102266450/163078181-ac64842b-614d-4f8f-985f-998de3f3960d.png)

* A. Table Outputs
In this analysis, we were tasked to analyze outcomes (successful, failed and canceled) within the theater parent category based on a launch date month. Based off the raw data, I filtered by parent category of theater and then displayed January-Decemeber. I like to start my analysis by looking at the table before charts. Clearly May (111) and June (100) look promising in terms of having 'success'. Yet, as we begin to look column of 'failed' campaigns, May (52) and June (49) had two of the three highest failure outcomes. In other words, we advise Louise to take a closer look at other months before deciding that a summer production is best. 
* B. Pivot Chart 
By observing the chart, it is once again clear that the dates of May-August have large figures for success. We also notice that on average Nov-December seem to peform poorly. Interestingly, May, June, July, and August seem to have a large ratio between successful and failed campaigns. For instance, we noticed that in the month of May 111 campaigns had success to only 52 failures or 2.13X difference. This is relatively consistent in each of these months, so we recommend Louise place her plays/theater productions in this time frame. Otherwise, we can also comment on the nature of cancelled productions. We noticed the most cancellations at May (166), and June (153). Ideally, a production launch anytime after April, but before June seems to be the most ideal. 

### Analysis of Outcomes Based on Goals
- Conclusion about the Outcomes based on Goals:
![Outcomes_Vs_Goal](https://user-images.githubusercontent.com/102266450/163078205-27e21943-51a6-4ea8-b99d-0a9fceb961c3.png)

* A. Table Outputs 
In this section, we analyzed the percentage of successful, failed, or canceled outcomes by subcategory play versus the goal funding amount. We used the CountIfs function to capture this output, with a series of ranges for each goal fund. Our range varied from as low as $1000 to $50,000+ in goal funding. In short, we saw that success was found at a higher rate when the goal was less than $5000. This makes sense logically, and was supported when we saw figures dropping in success rate as the fund goal increased. Please note that the filter of subcategory play showed no canceled output---so this remains at zero. 
* B. Line Chart
Taking a closer look, we also observe that at $15000 to $19999 funding goal, both the percentage of success and failure meet at rougly 50%. We also notice large differences in percentage at the goal of $45000 to $49999. We anticipated that a large goal amount would translate to large failures rates, and it did, by hitting 100% failure (0% success). 
Our recommendation to Louise is clear, aim to set goals under $5000 if you want a high success rate---and if less conservative, do not pass the $15000 to $19999 threshold referenced before. There is a rate of diminishing returns after this point; in other words, as you continue press for higher funded goals, you will see more failures to meet such lofty amounts. 

### Challenges and Difficulties Encountered
- Limitations of this dataset:
![Screenshot 2022-04-05 200308](https://user-images.githubusercontent.com/102266450/163079222-078a5663-2c18-4642-9d8c-79a5c6c1d433.png)
![Screenshot (334)](https://user-images.githubusercontent.com/102266450/163079231-9ba8920a-8b89-43ad-ac15-b25f8f847cc7.png)

The primary issue I encountered was through my orignal sheet. I found difficulty in matching my box plot numbers, and a matching logical outputs in the Outcomes based on goals line chart. I approached the problem by taking a step back, and asking if it were a syntax or filtering issue. In short, it was a laspe in my judgement with an inconsistent subcategory filter and the creation of a column to track percetnage funded between the goal and pledged columns that held my errors for each. Upon editing, both outputs were successful or as expected. 
I did find a limitation by not holding the complete kickstarter data. As I did not collect or meet with the data collection team, it was a bit difficult at first to give a proper pass of numbers and understanding why each column was created. I did noticed that the date ranges are a bit old, so including up to at least 2020 would help create a more accurate recommendation for Louise. Although, with over 4000 datapoints, I would recommend looking towards VBA or Python and creating an automated process to create these charts. 

- Possible Tables/graphs to create: 
![Louise Parent Cateogry Outcomes](https://user-images.githubusercontent.com/102266450/163078860-163451ec-17d0-4857-b042-e741df00ac48.png)

As referenced in the limitations section, at times I found myself questioning if VBA could present my charts in a more efficient way. A analysis that compares more than the current focused subcategory of plays would benefit Louise. She held the majority of her focus on Great Britain, and would hope to expand our current charts to overlay with more demographic or geographic data. In general, if we can at least run similar analysis for other subcategories, we could build a case for Louise to continue her focus on plays, or pivot towards another category altogether. 











