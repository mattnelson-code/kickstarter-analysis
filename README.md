# Kickstarting with Excel

## Overview of Project

* Louise wants to optimize the results of her kickstarter campaign for her play *Fever*
* Kickstarter data will be used to visualize campaign outcomes based on their launch dates and their funding goals
* Written report will include analysis and visualizations 

### Purpose

* To aid Louise in optimizing her kickstarter campaign 
* Purpose will be achieved by performing analysis on Kickstarter data to uncover trends and present discoveries 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

* PivotTable created using Kickstarter data to visualize outcomes based on launch date 
* Filter the Parent Category to theater to show data related to Louise's campaign
* See chart: ![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

* Goal ranges created to visualize outcomes based on goals 
* Chart shows successful and failed outcomes for each goal range
* See chart: ![Outcomes_vs_Goals](Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

1. Outcomes Based on Launch Date - For this visualiztion it is difficult to pinpoint other explanatory variables that may have led to successful and failed campaigns. This visualization suggests May and June are the best months to start a campaign, but other important questions remain unanswered. For example, did campaigns from those months tend to have lower goals? Did campaign managers possess superior fundraising skills? 
2. Outcomes Based on Goals - Creating goal ranges poses a challenge, but this challenge can be solved using the COUNTIF function on Excel. In addition, there is a small sample size for high goal ranges. This small sample size most likely leads to unexpected results. For example, percentage successful trails percentage failed for the $25000-29999 goal range but exceeds the latter for the $35000-39999 goal range. With a larger sample size, percentage successful would likely decrease as the goal range increases, although this is not definite due to other factors (such as the campaign manager's fundraising skills). 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. Start in May or June. May and June have the most successful campaigns and have more successful campaigns than failed campaigns. 
2. You miss all of the shots you don't take. Five months have fewer than 100 total outcomes, and 3 of the 5 are in the winter (November, December, January). Furthermore, these 3 months account for the 3 of the 4 fewest successful outcomes. This fact indicates that when more people try, more people succeed. 

- What can you conclude about the Outcomes based on Goals?

1. The 4 lowest goal ranges have a higher percent successful than percent failed, which makes sense since lower goals require receiving less donation money. For the $15000-19999 goal range, percent successful and percent failed each equal 50%. For the higher goal ranges, the higher percentage alternates between percent successul and percent failed. 
2. The difference in the data from the low goal ranges and the high goal ranges is the sample size. A likely hypothesis would be the following: As the goal range increases, percent successful decreases. For the low goal ranges, this holds true. However, for the high goal ranges, the higher percentage alternates between percent successful and percent failed. It is important to note that the low sample size for high goal ranges makes this data less reliable, as it has a higher margin of error. 

- What are some limitations of this dataset?

* A limitation of the data set relates to the difficulty of measuring the campaign manager's fundraising skills. The data presented in the analysis holds fundraising skills constant. However, it seems that the ability to meet a goal in large part depends on the campaign manager's work ethic and skill set. 

* Another limitation of the data set (though less significant) relates to the overall sample size. A greater sample size most likely makes the data more reliable. That said, the Kickstarter data's sample size makes the analysis worthwhile, and the above conclusions deliver insight that can benefit Louise's kickstarter campaign.

- What are some other possible tables and/or graphs that we could create?

* Building on the limitations section, it seems that a useful chart would convey the outcomes based on work ethic. Work ethic could be measured by hours of fundraising per week. A hypothesis would predict a positive correlation between hours of fundraising per week and successful outcomes, and a chart would show the precise amount of minimum hours per week that generated a successful outcome.

* On the other hand, it is important to look at a potential chart using the collected data. A useful chart would reveal desired locations for a kickstarter campaign by showing outcomes based on country. Perhaps certain countries impact outcomes more than others, which would be useful information to present to Louise. 
