# Kickstarting with Excel

## Overview of Project

### Purpose: 
To learn how to use various Excel functions to analyze large amounts of data in a compact, readable format that can be used to help a client understand the data and its outcomes in how it relates to their needs.

## Analysis and Challenges: 
By filtering out kickstarters that didn't relate to Louise's situation, such as technology, the resulting data wasn't skewed by the success and failure of kickstarters in outlier situations.  Only the data that would help the client in her own endeavors in the theater were needed in aiding her own success.  

### Analysis of Outcomes Based on Launch Date
It’s apparent that kickstarters relating to the theater are most successful in the late spring and early summer.
![Theater Outcomes by Lauch Date.png](https://github.com/HopeAkrout/kickstarter-analysis/blob/main/resources/Theater%20Outcomes%20by%20Launch%20Date.png)]

### Analysis of Outcomes Based on Goals
It appears that when the goals are set lower, there is a higher success rate, and there is a steady decline as the goals get higher.  What’s interesting to see is the outlier of the higher goals between $40,000.00 to $49,999.00 have a spike showing a much high success rate, though the total number of projects is too small a pool to make hard and fast determinations.  It could be attributed to the popularity of the play, success in garnering awareness, etc. and not something we have data on to verify.
![Outcomes vs Goals.png](https://github.com/HopeAkrout/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The most challenging aspect of sorting the data was the COUNTIFS formula and figuring out which columns were needed to filter out the unrelated lines.  The second challenge was that the line chart automatically determined the axis data and I had to redefine my data criteria to create the desired chart format with percentages on the y-axis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The most successful time to launch a kickstarter is in May, and become more likely to fail in the Autumn and winter.

- What can you conclude about the Outcomes based on Goals?
Kickstarters with a goal of $1000-$4999 have the best probability of success.

- What are some limitations of this dataset?
Though we can narrow down the data by country and year, we can’t further narrow it down to how the kickstarter was promoted to reach an audience that would pledge as well as spread word to their social circle to spread awareness.

- What are some other possible tables and/or graphs that we could create?
A graph could be created to determine how long each kickstarter lasted from launch to deadline.  Part of the success and failure could be attributed to how long a kickstarter was given to reach their goals.  We could drill down further into how many backers successful kickstarters had and the average donation.

