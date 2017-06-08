This syllabus lives at http://bit.do/gads101

# Learning Objectives
- Explain the field of data science, defining common roles, benefits, and trends.
- Explore some popular tools and resources to visualize, analyze, and model data.
- Recognize the different types of problems that can be solved by data scientists.
- Apply the data science workflow to provide real world recommendations.

# Agenda
0. [5m] Instructor Intro
1. [5m] Class Setup / Protocol
2. [10m] Student Intros
3. [15m] Question Set: Data/Analysis/Science
4. [20m] Categories of Data Science, Definitions
5. [10m] Data Science Roles, Benefits & Trends
6. [10m] Skills & Career Trajectories, Q & A
7. [5m] BREAK
8. [20m] Getting started with `pandas`
7. [20m] Intro to some data science models
10. [50m] Breast cancer detection example
11. [15m] Next Project Ideas, Steps, Q & A
12. [5m] Closing

# Question Set 1
1. What is data?
2. What is data analysis?
3. What is data science?
4. What's the difference?
5. Why do it? What's the value?

# Question Set 2
1. What is a prediction?
2. What do you base it on?
3. How do you know it's good?

# Question Set 3
- Suppose you have 10,000 documents written in a foreign language you couldn't understand.
- The documents are uncategorized
- You need to organize them into piles of 100 somehow, ideally similar documents going in the same pile.

How would you do it?

# About Data Science
## Categories
- supervised learning (regression, classification)
- unsupervised learning
- applied statistics

## Roles
- data analyst
- data engineer
- data scientist
- business-product-data liaisons

## Trends
- collecting more data
- being data-driven is table stakes
- Python

# Skills, Trajectories
## Data Analyst
- SQL
- Excel
- Python for data analysis
- Pandas

## Data Engineer
- Python for data analysis and general software engineering
- Pandas
- SQL
- Basic machine learning

## Data Scientist
- Python or R
- Strong machine learning skills
- Linear algebra
- Statistics

# Python warmup & documentation exercise
0. Generate a random integer between 1 and 130.

# Getting started with `pandas`
We're going to use this set of data: https://s3.amazonaws.com/python-level-2/sales-funnel.csv

## Prelim
- What is Exploratory Data Analysis (EDA)?
- What is our current data set about?
- What questions would you ask about the data?

## Basic Manipulation of the Data
0. Let's read in the data.
1. How do we see what columns are available?
2. How do we look at just the head or tail of the dataset?
3. How do we look at only a few rows?
4. How do we only look at certain columns?
5. How do we pull out a column and look at it as a series?

## Filtering DataFrames
- How do we look at only those rows that have Status = won
- Exercise: How many accounts have a price greater than $12,000?
- How do we get the maximum value of a certain column?
- What is the minimum account price? The mean? The sum? The standard deviation?

## Intro to Visualization
- Demo of pivoting
- Plotting from `pandas`
- A sneak peak into Plot.ly

## Exercise
Read in [this new data set](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/datasets/breast-cancer.csv) and do some exploratory data analysis (EDA) on it.

[Here's the documentation](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names) about the data set.

- How many rows do we have?
- How many columns?
- What are the column types?
- What are the descriptive statistics?
- What do the columns mean?

# Intro to some data science models & algorithms
## Supervised learning models
- Linear Regression
- Random Forests
- Neural Networks
- kNearestNeighbors Algorithm

## Unsupervised learning algorithms
- Principal Component Analysis
- K-Means Clustering
- Hierarchical Clustering

## Exercises
- [kNN in 1 dimension](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/worksheet_1_kNN.pdf)
- [kNN in 2 dimensions](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/worksheet_2_kNN.pdf)

### Questions
- What if k is too big?
- What if k is too small?

# Breast cancer detection example
- [Cross-validation](http://scikit-learn.org/stable/modules/cross_validation.html)
- [K Neigbors Classifer](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)

## Demo of model-building
We'll walk through building a predictive model using the kNeighbors classifier.

- What is target? feature?
- What is a validation set vs training set?
- What is a model?
- What is "fit"?
- What is model-tuning?

## Exercises
0. Create two variables, one equal to the target, the other equal to the feature set
1. [Together, following instructor] build the model.
2. Try different values of k. Which k do better?
3. Plot model accuracy against different values of k
4. Once you've fond the optimal k, use the RandomForest and LogisticRegression to classify this dataset and see how it compares to kNN.

# Next Projects, Ideas, Steps, and Q & A

# Closing
