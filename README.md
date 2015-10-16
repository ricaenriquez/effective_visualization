effective_visualization

**********************
Summary
**********************
The following charts depict MSP flight status data from the US Department of 
Transportation's Research and Innovative Technology Administration (RITA - 
http://stat-computing.org/dataexpo/2009/the-data.html). On-time, delayed, and cancelled 
flights conditions can be seen for various time spans. The information can be used to see
good/bad times to fly in/out of MSP. The user has control on filtering by months and years.

The visualization can be seen at: http://bl.ocks.org/ricaenriquez/raw/c66bc4c67c8e699ee474/

**********************
Design
**********************
The main plot I wanted to show is the middle chart, which divides the flights by day of 
week and time of day. The bars throughout the page are colored by flights status. I 
thought a stacked and grouped bar chart would best show when the best and worst times to 
fly in/out of MSP are. I also thought it would be nice to see percent plots for the given 
months and years. Additionally, seeing the total number of flights in each category for 
the given data is given. The plots were arranged so that the tooltips did not get cutoff 
on the screen.

I was able to figure out how to keep the bars for months and years the same size by 
filtering the months chart only by year, and the years chart only by months.

**********************
Feedback
**********************
There was an initial problem with filtering data because it was not filtering for both 
months and years, just one type.

**********************
Resources
**********************
In addition to the course work template, I used the dimplejs.org advanced examples:
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends

I was also inspired by two projects that was brought to my attention on the forum/google
plus:
https://github.com/cmiller112000/ud-datavis
http://cdn.rawgit.com/cyuancheng/Data_Visualization_D3js/master/index_re8.html
