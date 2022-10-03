# Kickstarting with Excel

## Overview of Project
Louise will reach her fundraising goal soon and wants to have more information for decision making on her endeavour, Fever's play. This analysis,was based on historical data for Kickstarters projects. Especifically, the report will delimit the focus on theather plays and will adress two main concerns: Outcomes based on lauch dates and Outcome based on fundraising goals. 

### Purpose
The main porpuse is to show Louis (client) through data analysis how similar projects behaved so she can make informed decisions on lauching date and budget management based on historical information.  

## Analysis and Challenges
The analysis began with observing the type of data contained in the data set. Cleaning it and making the calculations available in columns to perform the analysis with pivot tables.

After data was clean and structured in columns, it could be used to feed two main pivot charts:
- Outcomes based on launch date.
- Outcomes based on goals.


### Analysis of Outcomes Based on Launch Date
 
In the line plot below, the outcomes of theather category are shown based on launch date.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/114015620/193632183-436a6cf6-d4f7-4c40-8d21-bc3660df798b.png)

According to the graph, the following conclusions can be drawn:
- The best month for launching is May and June. 
- August, October and December are the worst months to launch, the risk of failure is the highest.  
- Only 37 of all projects were canceled. 
- Overall 61% of the projects were successful, 839 out of 1,369.



### Analysis of Outcomes Based on Goals

In the following line plot, classes were formed out of delimited fundraising goals to show success, failure and cancellation rates of plays from the data set. 

![outcome_vs_goals](https://user-images.githubusercontent.com/114015620/193633078-81416c4d-af04-49d6-8d8d-c294199c1fa0.png)

We can conlude that:
- The most succesful plays had a fundraising goal in the following intervals <1.0 K-4.9 K & 35.0 K-44.9 K.
- The lowest succesful rates were in projects with a goal between 25.0 K-34.9 K. 
- The greatest concentration of projects is located in the interval of <1.0 K with a success rate of 76%. 

### Challenges and Difficulties Encountered

The first challenge came when the dates where in a different format than the one excel recognizes. The data in this column had to be transformed. The second challenge was to correctly categorize data, into parent category and subcategory to later display them adequately on pivot charts. The third challenge was to transform data into a useful indicator. A column labeled as average donation was created to know on average how much backers invested in the project.  By doing this, some errors appeared whith this calculation so debugging was necessary. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - The best month for lauching is May and June.
  - December is the worst month for lauching.

- What can you conclude about the Outcomes based on Goals?
  - The most succesful projects are the ones with fundraising goals less than 1,000 with a success rate of 76%. 

- What are some limitations of this dataset?
  - Parent category and subcategory were not correctly split, so extra work had to be done in data set. 
  - Date format also needed to be modified to be used in the analysis. 
  - There was not a universal currency, in case we want to analyse projects between countries, there is no standard currency. If US dollars were defined as the currency, a standard currency column must be created to convert all currencies. I found this crucial because if omitted, comparisons will be wrongly calculated so decisions based on this will be invalid.  

- What are some other possible tables and/or graphs that we could create?
  - For porcentages I found heat map more useful or even a table with scale bar color. I believe it is more visual to idenfiy which months had highest success.
  - Another graph that could be of use is a chart of outcomes based on success rate and date of launching, kind of combining both charts into one.
   
  
