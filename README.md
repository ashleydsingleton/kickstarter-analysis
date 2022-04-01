# An Analysis of Kickstarter Campaigns

## Overview of Project

### Using the Kickstarter dataset and focusing on Theaters/Plays, we measured the success of different campaigns in relation to their launch dates and their funding goals. This is illustrated in a Theater Outcomes Based on Launch Date Chart and in an Outcomes Based on Goals Chart. By providing the charts to view the data you will be able to visualize and interpret the data in a more meaningful way. 
 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### During the analysis and creation of the Theater Outcomes Based on Launch Date pivot table and line graph, I found that May and June had the highest number of successful campaigns but they also had the higheset number of total campaigns launched. Even so, they still remain the recommended best months to launch new theater campaigns when considering the ratio of successful to failed in all months. 

### Analysis of Outcomes Based on Goals

#### The line graph created from this analysis provides the answer for us that Plays with a fundraising goal less than $2000 will be most successful and those under $4999 will be 2nd most successful. 

### Challenges and Difficulties Encountered

#### When working through the Outcomes Based on Launch Date, I imagine that a possible challenge could be during building the pivot chart due to the extra rows Excel creates when moving the "Date Created Conversion" field to Rows. Excel automatically creates 3 fields there, including Years and Quarters. We have to remove Years and Quarters in order for only the Months to remain on the Row Labels. One might also find a challenge in filtering the Parent Category and the Column labels. Fortunately, I have had some experience in these things and was able to navigate it with some ease. 

#### The Outcomes Based on Goals deliverable was more of challenge for me. After much trial and error, I was able to arrive at the final goal of providing an accurate line graph representing the Outcomes Based on Goal for subcategory Plays. The first challenge I ran into was getting my =COUNTIFS formulas setup correctly. I played with them a lot before I got them correct. My 1st biggest mistake was that my formula was only looking at the outcomes column and not the goals column for the amounts. Just when I thought I had everything fixed, I noticed that I was also supposed to filter on subcategory "plays." I went back and added that condition for the Subcategory column into each of my formulas and then rebuilt my line graph. Finally, the table results and line graph were correct! Figuring the sum and percentages were no problem for me since I've done those before. Getting the line graph correct was easy once I fixed my =COUNTIFS.    

## Results

### - What are two conclusions you can draw about the Outcomes based on Launch Date?
#### 1. In general, Theater campaigns are more successful than they are failures. 61% of Theater campaign outcomes were successful and only 36% failed. 
#### 2. May and June are by far the two most successful months for Theater campaigns, 211 total, representing 25% of the total successful. While December is by far the least successful with only 37 successful campaigns and almost as many failed with that number being 35. 

![Theater_Outcomes_Based_on_Launch_Date](https://user-images.githubusercontent.com/92938054/161184254-d1a69e3d-cd03-460b-be36-cc8f3fb457c5.png)


### - What can you conclude about the Outcomes based on Goals?
#### 1. Plays with goals under $1000 were almost 80% successful. 
#### 2. There was another spike to just over a 60% success rate in the $35,000 to $44,999 goal range. 
#### 3. Any plays with goals over $45,000 are bound to fail.

![Outcomes_Based_on_Goal](https://user-images.githubusercontent.com/92938054/161184409-96d1536d-44da-44f5-80bf-f4de8ca7585d.png)


### - What are some limitations of this dataset?

#### The dataset doesn't have any information about intended audience or primary demographic. This could be helpful when interpreting the data based on many factors. A student might be more available and have more funds in the summer when working to make a pledge versus during the school year. A CPA might be completely unavailable during the months of January through May but more apt to provide support during other months. If either of these are your target audience and they aren't available during your campaign dates, that could be a major cause for failure. 

### - What are some other possible tables and/or graphs that we could create?

#### We could provide additional information by creating a bar graph including the year which might give additional insight to the current day relevance of the data in case there has been a shift in audience interest. 	


