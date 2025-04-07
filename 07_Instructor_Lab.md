# Instructor-led Lab: Manipulating Data

In this assignment you will practice utilizing DataFrames in a program. 

For this lab, you will use the [github_teams.csv](/data/github_team.csv) which contains behavioral trace data extracted from GitHub.

## Accessing Data

Using the `github_teams` dataset, please perform the following operations in order:

* Open the file within Python.
* Find out what the column header names are.
* Determine the number of columns.
* Determine the number of rows.
* Determine which columns are categorical and convert them from *object* to *category*.
* How many unique values does `Team_type` have?
* How many unique values does `Team_size_class` have?
* * What is the value of the 63rd row and 6th column?
* What are the values for the 300th row?
* Using three different methods, select row with index value 595 with 1st, 2nd, 3rd columns.
* Using two different methods, select the row with index value 46 with the 3rd and 7th columns.
* Create a new DataFrame for the column `bot_work` using two different methods.

## Sorting and Ordering data 

Now that you have learned to subsample data, it is your turn to apply your new knowledge. Using the `github_teams` dataset, please perform the following operations in order:

* Select `human-bot` teams that have a `bot_members_count` value greater than and equal to 2.
* Find the `human` teams that are `Large` and have a `human_gini` value greater than and equal to 0.75.
* How many teams are in the `Small` or `Large` category?
* How many teams are in the `Small` or `Large` cateogry with a `human_gini` value less than and equal to 0.20?
* How many `human-bot` teams are in the `Medium` category?
* Create a subsample of 50% of your data.
* Create samples for a 8-fold cross validation test.
* Select columns that are numeric and save it as a new DataFrame.
* Remove the columns `bot_PRReviewComment` and `bot_MergedPR` from the DataFrame.
* Save the columns `Team_size_class` and `human_members_count` as a new DataFrame.
* Rename these two columns in the new DataFrame.

Save your notebook with output displayed within it and submit for grading.