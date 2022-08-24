
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

I performed my analysis here by creating a Pivot Table. The Pivot Table allows me to organize the data to begin to storytell from a date perspective. By filtering by Parent Category, I was able to create the table only with that data included, which is what is relavant to Louise. By including outcomes in both columns and values, I was able to see if campaigns were successful, failed or canceled against months. While there were no formulas used to create this Pivot Table, I was able to create a timeplot that visualizes the data in the table. 

/Users/nsiegel/Desktop/bootcamp/Resources/Theater_Outcomes_vs_Launch.png


### Analysis of Outcomes Based on Goals

I performed my analysis here by using COUNTIFS formulas, as well as creating a timeplot. I also used AVERAGE formula, and some simple division to find percentages. The COUNTIFS formulas are quite intricate, incorporating two separate columns and two sets of greater than/equal two conditions. 

/Users/nsiegel/Desktop/bootcamp/Resources/Outcomes_vs_Goals.png


### Challenges and Difficulties Encountered

The main challenges I faced while creating the pivot table was grouping the data to only show months. After a little Googling, I was able to figure out how to show the table properly.


The main challenges I faced while creating the Outcomes Based on Goals sheet was my COUNTIFS syntax. I originally was able to create the timeplot without any issues, but after crosschecking my work with the timeplot the directions provided, I realized my data was off. I had to go back into my formulas and check my greater than/less than signs, as well as the table ranges to ensure they were referencing the right columns in the dataset. Evenutally I found my mistakes through editing the forumulas a number of times. I also reached out to the class to ask how they solved the analysis.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

According to the Pivot Table Theater Outcomes and Launch Dates, I can conclude that it is more favorable to launch a crowdfunding campaign in the summer months, namely April-August. May and June particularly have almost double the amount of successful campaigns as they do failed. Another conclusion I can draw from this Pivot Table is that December is the least favorable month to launch a fundraising campaign, as the number of successful campaigns only tops the number of failed campaigns by 4.

- What can you conclude about the Outcomes based on Goals?

I can conlcude that based on the timeplot of Outcomes Based on Goals, the higher the goal fundraising amount is, the less successful the campaign will be. Similarly, the smaller the fundraising goal amount is, the more likely the campaign will be successful. Between $5,000 and $25,000 as a fundraising goal is when the chances of failure and success are the most even.


- What are some limitations of this dataset?

Limitations of this dataset include how recent the data is. The most recent data is pulled from 2017, which is 4.5 years ago. Another limitation of this dataset is the possibility that the data was not entered properly, hence creating unaccurate results.

- What are some other possible tables and/or graphs that we could create?

Another possible table we could create is outcomes based on geography. It could be helpful for Louise to know which countries provide the most promise in terms of fundraising. We could create a bar graph here to showcase that data. Another idea is to create a graph that depicts which categories required what amount of fundraising to reach their goal. This could give Louise some insight into her potential category competitors, and ultimately steer clear of, or capitalize on, specific time of year or countries based on that data.
