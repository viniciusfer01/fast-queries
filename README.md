# Introduction
This is a project based on the Guided Project: Building Fast Queries on a CSV" (from Dataquest's "Algorithm Complexity" course):

## Objective
Adapt the solution made for the guided project to a [new database](https://www.kaggle.com/datasets/pavellexyr/the-reddit-climate-change-dataset).

To do this, three main functions were implemented. The first function receives an id from a reddit message and returns all the information about that message. 

The second function is given an upper bound and a lower bound, and it returns all the messages that have a 'sentiment' row within the interval. 

The third function receives a target value and searches for two comments whose 'score' can be added to result in the target value. If there is no such values, the function returns -1.
