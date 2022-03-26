# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
Louise is looking to initiate a Kickstarter campaign for her latest creation, a play entitled "Fever".

### Purpose
Louise would like an analysis of recent Kickstarter campaigns to determine if there are any characteristics shared amongst successful campaigns.

## Analysis and Challenges
An analysis was performed on a selection of over 4000 various Kickstarter campaigns, ranging from potential films to unique inventions.

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/michael999999999/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

The first analysis looks at Kickstarter campaigns and their rate of success based on launch month. As is immediately noticeable, campaign success rates spike through the summer months, with campaigns launched in May at the peak. As the holiday season approaches however, an obvious dip in success rate occurs beginning in October. Campaign failure rates, however, do not show any particular trend based solely on time of the year. Two pieces of advice would be to shoot for a May campaign launch date, and avoid launching the campaign during the holidays.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/michael999999999/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

The second analysis focuses on campaign outcomes relative to their goal funding amount. Predictably, campaigns with lower funding goals show a higher success rate, with the most successful campaigns having a goal of less than $1,000. As the funding goal rises, so too does the risk of campaign failure. Interestingly, campaigns with funding goals between $35,000 and $45,000 actually swap places, with more successes in this range versus failures. However above $45,000, the prior trend continues with more failures than successes as funding goals increase. The stakeholder Louise has a set a goal of $10,000 which, judging by the graph, would indicate her campaign has a slightly better than 50/50 chance of success. Campaign failures outpace successes almost entirely beyond $20,000, so as long as Louise stays below that amount, she stands a good chance of success. It is absolutely adviseable to not set a goal above $25,000, where campaigns failure sits around 80%.

### Challenges and Difficulties Encountered
A dataset this large definitely proved challenging as there were many methods required to weed out irrelevant data. Fortunately, a smaller, more focused compilation of data was able to be extracted. Additional data would be useful in creating an even better picture of Louise's campaign chances. One piece of information that could be greatly beneficial would be to see the genres of successful plays, to determine if one is more successful than another. Additionaly, info such as minimum and maximum donation amounts could also create a better analysis, as we could see if any donations heavily skewed the mean donation. 

## Results
In summary, it would seem as though Louise's goals are completely within the realm of possibility. Her goal funding amount of $10,000 seems entirely doable, and theater appears to be popular on Kickstarter. As mentioned earlier, I would recommend starting the campaign in the late spring or early summer for the best chance of success.
