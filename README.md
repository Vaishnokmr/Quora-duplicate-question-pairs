
# Quora-duplicate-question-pairs

A brief description of what this project does and who it's for


## Problem Statement
Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

> Credits: Kaggle 

- Identify which question asked on Quora are duplicates of questions that have already been asked.
- This could be useful to instantly provide answers to questions that have already been answered.
- We are asked with preciding whether a pair of questions are duplicates or not.


## Sources/Useful Links
- Source : https://www.kaggle.com/c/quora-question-pairs
____ Useful Links ____
- Blog 1 : https://engineering.quora.com/Semantic-Question-Matching-with-Deep-Learning
- Blog 2 : https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30
## Real world/Business Objectives and Constraints
    1. The cost of a mis-classification can be very high.
    2. You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
    3. No strict latency concerns.
    4. Interpretability is partially important.
## Machine Learning Problem
#### Data Overview:
- Data will be in a file Train.csv 
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate 
- Size of Train.csv - 60MB 
- Number of rows in Train.csv = 404,290

#### Type of Problem:
It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.

#### Performance Metrics:
* log-loss : https://www.kaggle.com/wiki/LogarithmicLoss
* Binary Confusion Matrix
## Technology


[![Programming Language](https://img.shields.io/badge/Language-python-green.svg)](https://www.python.org/)
[![Tools](https://img.shields.io/badge/Tools-NLP-yellow.svg)](https://en.wikipedia.org/wiki/Natural_language_processing)
[![Machine Learning](https://img.shields.io/badge/MachineLearning-RandomForestClassifier-red.svg)](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
[![Visualization](https://img.shields.io/badge/Visualization-Plotly-black.svg)](https://plotly.com/)




