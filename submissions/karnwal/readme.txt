******************************************************
Name - Shantanu Karnwal
Course - INFO 5602 - Information Visualization
Instructor - Prof. Danielle Szafir
Project 1 - Visualizing Anscombe’s Quartet
******************************************************

Part 1: Interpreting Data
---------------------------
Implementation done exactly as given in the directions specified in the problem description. Code was written in the exact same way as dicussed in the lecture.

Part 2: Building Scatterplots
-------------------------------
Again repeated the exact same approach as shown in the lecture. There were a few problems in implementing it directly just by copying the code as it is from the class, with the problem being that I was not able to see the plot for all the points in the csv. Turns out - we need to change the data type from string to integer/float as data is read as default in string form. Did this by adding '+'d[xVal] and similarly '+'d[yVal], in which appending '+' sign does that conversion.
Thanks to : https://github.com/d3/d3/issues/2912

Part 3: Building Line Graphs
------------------------------
Most of the inspiration for this part is taken from the link - https://bl.ocks.org/d3noob/6f082f0e3b820b6bf68b78f2f7786084, but I have kept the code as much similar to the lecture as possible. Doing this was making the line graph but it was connecting most of the points, instead of connecting just the points in increasing order of x's. To get rid of this problem, I got help from this link - https://stackoverflow.com/questions/13645446/sort-data-for-d3-js-path, which essentially told that I have to sort the points in the order of x's and then plot the line graph.

Part 4: Interaction
---------------------
Pretty straightforward. Got some help from: https://stackoverflow.com/questions/23703089/d3-js-change-color-and-size-on-line-graph-dot-on-mouseover

Part 5: Building Multiple Charts
----------------------------------
Had to add on code in the css file to incorporate 4 visualizations in the same row. Also added code in html file to show which visualization is for which dataset. Got some help from - https://stackoverflow.com/questions/20694672/4-divs-side-by-side-menu-bar

Bell: Tooltips
---------------
Had to modify some part of part 3 code. Just replaced the 'click' function in part 4 with the 'mouseover' function. Pretty straightforward. Help from - https://stackoverflow.com/questions/10805184/show-data-on-mouseover-of-circle

Bell: Best Fit Lines
----------------------
Perfomed Linear Regression on the dataset. Calculated the predicted value y^ (or yhat) by first calculating the least squares estimates of b0 and b1 which are the intercept and the slope respectively. Then used the formula y^ = b0 + b1.x to get the best fit line. Links which I used for help - 
1) https://bl.ocks.org/ctufts/674ece47de093f6e0cd5af22d7ee9b9b
2) https://onlinecourses.science.psu.edu/stat501/node/252


