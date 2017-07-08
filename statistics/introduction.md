
# Introduction To Statistics

These are notes captured from the [Udacity Intro to Statistics Course.](https://www.udacity.com/course/intro-to-statistics--st101)

## Looking At Data

### Scatter Plots
Scatter plots are way to visualize the relationship between two variables. If the two variables are related then there is "linearity" in the graph and we can predict the value of one variable given the value of the other variable. If the graph consists of random points scattered all over the graph then the variables are not related. We cannot predict one variable's value based on the other variable.

### Bar Charts
A bar chart can be used to show comparisons among categories. A bar chart is a common way to view **categorical data**. A common type of bar chart is a **histogram**. A histogram shows the *frequency* at which categories appear in a data set. For example, if we ask a group of people what their salaries are we will get a range of answers. If we sort the salaries from lowest to highest and put them into groups ($50,000 - $60,000; $61,000 - $70,000 and so on) a histogram would show the frequency at which each grouping occurrs - e.g., 5 people in the first group, 10 people in the second and so on.

### Pie Charts
Pie charts are used to view relative data. A pie chart shows the relative proportion of quantities. For example, there is an election with two political parties. One party gets 60% and the other gets 40%. This pie chart would have on slice that takes 60% of the pie and another slice that takes up 40%.

### Programming Charts
This is an optional module but, since this is a study group whose purpose is technology and programming, it is probably a good idea to do it. It uses a python library called "plotting". This is not a standard graphing library so don't bother googling it. It is a Udacity specific library that is actually a wrapper for matplotlib - which *is* a standard graphing library. Details and instructions are [here](https://www.udacity.com/wiki/plotting-graphs-with-python#!#overview). One side effect of going through the exercise of using this library as opposed to just using matplotlib is that, if your python skills need work, you get to see the source code and you can get practice working in the python environment.

## Statistics Can Be Misleading

### Simpson's Paradox
Simpson's Paradox is a famous example of how statistics can be misleading. Specifically, in this phenomenon a trend can appear in individual groups but when the groups are combinded the trend disappears. There are many canonical examples but in a nutshell it goes like this:

There are two baseball players, Player1 and Player2. In each of three seasons Player2 has a higher batting average than Player1. (Batting Average is a percentage and is calculated by dividing "Hits" by "At Bats".) However, when the three seasons are aggregated Player1 actually has the higher overall batting average!

Player | Season1 | Season2 | Season3 | Combined
-------|---------|---------|---------|---------
P1 | 12/48 (.250) | 183/582 (.314) | 190/654	(.291) | **385/1284 (.300)**
P2 | **104/411 (.253)** | **45/140 (.321)** | **163/495 (.329)** | 312/1046 (.298)	

The key takeaway is that statistics can be misleading and one can draw the wrong conclusions from them if they are not done correctly. One should be skeptical of statistics and one must really understand the problem in order to turn raw data into statistics.

A nice visual explanation of Simpson's Paradox is here: http://flowingdata.com/2013/09/19/a-visual-explanation-of-simpsons-paradox/
