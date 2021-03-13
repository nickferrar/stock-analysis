# Chapter 2 Challenge 

# Stock-Analysis

## 1. Project Overview:

Refactoring code that we created during Module 2 - VBA of Wall Street that analyzes stock options in order for the script to run faster. 

## 2. Results:

In the original code, running the analysis on 2017 runs in 0.5898438 seconds and the refactored code runs in 0.08203125 seconds
In the original code, running the analysis on 2018 runs in 0.5859375 seconds and the refactored code runs in 0.0859375 seconds

The image for 2017's refactored code runtime is: [2017](VBA_Challenge_2017.PNG)
The image for 2018's refactored code runtime is: [2018](VBA_Challenge_2018.PNG)

## 3. Summary:

The pros of refactoring code is that the functionality of the code can be greatly improved. This can help if the program is complicated or taking in huge amounts of data.
The data set for this project was small with only 12 data points and the improvement was half a second.

The cons of refactoring code is that it can cause issues and errors elsewhere in the code that might not be anticipated. If you are running on a tight deadline it wouldn't be 
advisable to refactor near the deadline. In this example however, it did not cause any issues as we were simply replacing the for loop with an indexing variable so that the code
runs less times. The changes in the code are here:

[Original](https://github.com/nickferrar/stock-analysis/blob/main/Original%20loop.PNG)
[Refactored](https://github.com/nickferrar/stock-analysis/blob/main/Refactored%20Loop.PNG)


