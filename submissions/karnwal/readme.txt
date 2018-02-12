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
