# Bikeshare_Analysis

An Interactive Experience
The bikeshare.py file is set up as a script that takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions on the previous page will change! There are four questions that will change the answers:

Would you like to see data for Chicago, New York, or Washington?
Would you like to filter the data by month, day, or not at all?
(If they chose month) Which month - January, February, March, April, May, or June?
(If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?
The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.

Remember that any time you ask users for input, there is a chance they may not enter what you expect, so your code should handle unexpected input well without failing. You need to anticipate raw input errors like using improper upper or lower case, typos, or users misunderstanding what you are expecting. Use the tips provided in the sections of the Scripting lesson in this course to make sure your code does not fail with an execution error due to unexpected raw input.

Your script also needs to prompt the user whether they would like want to see the raw data. If the user answers 'yes,' then the script should print 5 rows of the data at a time, then ask the user if they would like to see 5 more rows of the data. The script should continue prompting and printing the next 5 rows at a time until the user chooses 'no,' they do not want any more raw data to be displayed.
