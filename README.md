# kickstarter-analysis in Excel

## Overview of Project
The purpose of this analysis is to see how launch dates and funding goals influence the outcome of different campaigns. We are using the Kickstarter dataset as a source to analyse data and visualize the outcomes, in order to draw a conclusion for Louise’s reference in her fundrasing play.


## Analysis and Challenges
In this analysis, Excel is used as a tool to investigate Kickstarter dataset and do visualization by drawing line graphs. 

### Analysis of Outcomes Based on Launch Date
PivotTable in Excel is used to analyse how launch date affects the outcome of different fundraising campaigns. We displayed the result by months and sort the category in theater. A line chart is generated to overview the number of successful, failed and canceled campaigns launched in different months. 

In the graph shown below, we can see that number of successful campagin is on an increasing trend from January to May, and reaches the highest point in May, means most campaigns can success by launching in May. Then it decreases from June to the lowest record in December. In view of the failed cases, they are close to each other over the year, while May, June, July and October are roughly the same. Not much campaigns canceled, except January has relatively higher number but it is still a minority compare the the whole data size.

![graph_1_Theater Outcomes Based on Launch Date](Resource/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
We generated a table to calculate the successful, failed and canceled rate in regarding to different goal, to see if the goal has an impact on the outcome. Only campaigns in "play" category are considered since this analysis is for a play to reference. A line graph is drawn to overview the data. 

From the graph - "Outcomes based on Goal" shown below, we can see lower goal amount has higher successful rate and low failed rate. It reaches the same level with the fund raising goal amount is $15,000 to $19,999. And from this point, failed rate is getting higher than successful rate. However, there is a fluctuation at the range $35,000 to $44,999, successful rate leads. And there is a high failed rate and very low successful rate if a campaign targeted to raise more than $45,000. Since there is no canceled project in the category of play, so the cancellation rate is 0% regardless the fund raising goal. 

![graph_1_Outcomes Based on Goal](Resource/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
PivotTable is a powerful tool in data analysis, but it takes me time to test what data should be included and how to arrange them, since I am new to it. Besides, writing report on github is another challenges. For example how to include photo on RAEDME file, what are the formatting syntax and etc. To over come these difficulities, I mainly search in Google to find resources showing how to use PivotTable and learn about the formatting syntax about writing on GitHub. 


## Results
From the analysis of Outcomes based on Launch Date, we can conclude that May is the best month to launch a campaign since it has the highest number of successful record. While December is the worst month for launching a campaign because its successful rate is the lowest and with a relatively high failed rate. Besides, there is no drastic high failed rate in a specific month. It might be because there are other factors lead a campaign to fail other than launch date. 

From the analysis of Outcomes based on Goals, we can conclude that most successful campaigns have low fund raising goals. 

There are some limitations on the analysis, for example the Kickstarter dataset cannot represent every campaigns performances, though the data size is already over 4000. Secondly, the data is covered all over the world, so may not fully explain for the situation in specific country since cultural difference. Lastly, the dataset is not up to date, the most recent information is 2017, which is 5 years ago from now, the outcome might be different. 

To make this analysis be more sophisticated, we might need to measure the central tendency by calculating the mean, median and mode, to examine how spread the data is by taking quartiles into account, to considering the data distribution by looking at the standard deviation, and last but not least to identify if there is any outlines affecting the result. 