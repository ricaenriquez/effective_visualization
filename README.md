effective_visualization

**********************
Summary
**********************
The following charts depict MSP flight status data from the US Department of 
Transportation's Research and Innovative Technology Administration (RITA - 
http://stat-computing.org/dataexpo/2009/the-data.html). On-time, delayed, and cancelled 
flights conditions can be seen for various time spans. The information can be used to see
good/bad times to fly in/out of MSP. The user has control on filtering by months and years
for the explore on your own section.

The visualization can be seen at: http://bl.ocks.org/ricaenriquez/raw/c66bc4c67c8e699ee474/

**********************
Design
**********************
The main plot I wanted to show divides the flights by day of week and time of day. For 
this chart I wanted to show the flight status for each day of the week and each part of 
the day. The bars throughout the page are colored by flights status. While a line chart 
might be easiest to convey time trends, I thought a vertically stacked and grouped bar 
chart would be better to compare on-time flights and varying degrees of delays. For 
instance, some people may not care about a 5 minute delay. With the stacked chart it easy 
to lump on-time and short-delay flights together and focus attention to individual values.
As a result the best/worst times can be more clearly seen. Also, a vertically stacked bar 
chart can show ranking, part-to-whole, deviation, and temporal relationships. For 
additional charts, I used the same/similar bars for easier comparison.

In addition to breaking down the data into days of the week and time of day, 
I also thought it would be nice to see percent plots for the given months and years. The
months chart is used to see is there are any seasonal trends in flight status (such as 
holiday or weather related delays). 

In the Explore on Your Own page, the years chart is included to show if there were any 
years  that were particularly bad/good for travel (e.g., 2001 and 2003). Additionally, 
a bar showing the the average flight status for all the unfiltered data is given to 
compare more specific time periods to the whole group.

The plots were arranged so that the tooltips did not get cutoff on the screen.

I was able to figure out how to keep the bars for months and years the same size by 
filtering the months chart only by year, and the years chart only by months.

The main feedback given was on the proper frame rate duration. However, since the animation
was not helpful, it was removed.

After feedback from the reviewer, the structure of the visualization. Now there is a 
section to break down the main findings of the project. The story goes from viewing the 
best/worst day and time to travel to looking at the flight status by specific months. The
story then focuses on winter and summer holiday travel to find the best times to travel
during those busy times.

**********************
Feedback
**********************
There was an initial problem with filtering data because it was not filtering for both 
months and years, just one type. This led to inconsistencies in the months/years charts. 
(in person demo)

The wording of the main directions was clarified.
I removed a pause after clicking the filtering bars since this led to a delay in the 
	animation.

The charts were paused at first, which allowed the user to start the animation.
(facebook data analyst nd cohort group)

The animations/filters were too slow for one user, so I increased the frame rate.
(Udacity Team chat room)

The animations/filters were too fast for another user (after the change above), so I 
decreased the frame rate.
(Udacity Team meeting)

There was a delay in the animation indicator and chart changes. I've sped up the animation
indicator change to make it clearer.
(Udacity Forum)

There was confusion by the animation in terms of the timing and importance. As a result, I 
removed the animation and now allow simple filtering of arrivals/departures.
(Project Review)

A user suggested making all the bar plots vertical/horizontal for easier comparison. I 
chose to make them all vertical so that the temporal trends could be seen better.
(Udacity Forum)

The story I wanted to explain with the data was not clear. I changed the site a lot as a 
result. I make one site more of a story and clearly point out the facts with supporting 
plots. However, I keep the ability for the user to  explore the data further.
(Project Review)

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

For information on chart types I used:
http://www.perceptualedge.com/articles/misc/Graph_Selection_Matrix.pdf
