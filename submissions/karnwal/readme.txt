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
