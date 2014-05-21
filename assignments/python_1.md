Python Assignment 1: PDS Spring 2014
------------------------------------

Please download student skill survey results [here](https://raw.githubusercontent.com/jattenberg/PDS-Spring-2014/master/data/survey_anon.txt). Use the unix wget or curl utility. The file is in a tab-separated data format, the rows of this data correspond to: 

student_id, command line experience, relational database experience, programming experience

For the following questions, collaborate with your group to find the right approaches, but please do the final work yourself. Use python to find the answers. Upload both your code and the responses to github in a dedicated folder. Post the link to the folder on github to NYU classes.

1. Which discipline (unix, database, or programming) would you say has the highest overall skill level amongst the students responding to the survey? Which discipline has the lowest?
2. Using matplotlib, make a plot of the distribution of skill levels, starting from the lowest and going to the highest for each of the three disciplines. You may wish to substitute the strings describing the skill level with a numeric value.
3. Combine these three plots, overlaying them on a single graph. Make sure each line is a different color for each line, and make a legend to tell the different colors apart. Hint: use google to figure out how!
4. Repeat question 3 but with a bar plot.
5. There are many times where a data scientist gets some columnar data and wants to simply plot it. Make a python script (a .py file) that can a take single column of numerical data from the command line via a unix pipe display that data in a plot. Hint: use the stdin function in the sys module.
6. Make a script similar that used in question 5 that makes a histogram instead of a line plot.
7. (bonus) Extend question 5 so that the script can read multiple columns of input data instead of just 1. Plot them together in the same plot window.