# Kickstarting with Excel

## Overview of Project

### Purpose: The purpose of this analysis is to advise Louise in her Kickstarter for her play. She’s curious about how different campaigns fared in relation to their launch dates and funding goals. By creating these charts, we’re able to visually show how different campaigns performed, and allow Louise to gather quick insights from the data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 
The first sheet was a pivot table, in which I filtered by “Years” and “Category” and then had “Outcomes” in the legend and values sections, and the “Date Created Conversion” (so that the date was in a legible format) in the categories section. From there I created a line graph that showed the outcome of theater Kickstarter campaigns based on the month the campaign was launched.
 
### Analysis of Outcomes Based on Goals 
On the second sheet, I used the COUNTIFS function to create a table counting the number of successful, failed and canceled play Kickstarter campaigns within a given funding goal range. From there I was able to determine the percentage of successful, failed or canceled play campaigns and use that data to create the second chart.

### Challenges and Difficulties Encountered 
I encountered two challenges during this section. The first was ensuring that I was properly using the COUNTIFS function. At first, I thought it should be nested, the way we used the IF function in class. However, I continued to get error messages before realizing that I needed to do two separate criteria ranges for the top and bottom goal numbers. I also did not include equal signs in my ranges the first time, and accidentally set the final criteria to theater instead of plays. Once I reviewed my work and fixed these mistakes, my graph looked like the one shown in the assignment and I knew I had done it correctly.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date? 
The first graph, Outcomes based on Launch Date, shows how theater campaigns performed based on the month that the campaign was launched. As you can see, the greatest number of successful campaigns were launched in May. However, it looks like this was also the month with the highest number of failed campaigns. From this, we can reasonably conclude that the most campaigns are launched in May.
 
- What can you conclude about the Outcomes based on Goals? 
The second graph, Outcomes Based on Goal, shows how play campaigns performed based on the amount of funding that they asked for. For the most part, plays with a higher funding goal are more likely to fail. However, plays around $35,000-$44,999 seem to be the exception, with most of those plays being successfully funded. However, this data is a little bit harder to generalize, as the bulk of the plays were asking for under $10,000 in funding. That portion of the graph (the first four points on the x-axis) represents over half of the plays on Kickstarter, while the other portion represents a much smaller portion.

- What are some limitations of this dataset? 
One limitation is that this data only represents the data available on Kickstarter. There are likely many other ways that theater projects get funded. And as I mentioned above, the data is skewed a bit as the majority of plays fall within a certain funding range. When it came to plays asking for funding over $25,000, there were far less of those than plays asking for funding under $25,000. And of course, there are always other factors that the data can’t capture. Did any of these plays have a celebrity involved, which got them more attention? Were any of the topics of the plays something really timely, that people are passionate about? These factors are hard to include in an analysis of this type, but could have an impact on whether a play gets funded. 

- What are some other possible tables and/or graphs that we could create?
Another helpful graph that could be made includes one comparing the duration of the campaign to its success. You could determine the duration of the campaign by creating a new column with the difference between the start and end dates. I would be interested to see if campaigns with longer durations have a higher rate of success. 
I would also be interested in doing a deeper dive into the data for plays that asked for similar funding numbers to Louise. I would want to analyze the performance of those campaigns against their launch dates and the duration of their campaigns, to give Louise a more personalized look into how she could expect her play to perform.
