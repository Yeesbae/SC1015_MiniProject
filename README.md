# Welcome to SC1015 Mini Project
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on predicting IMDB Rating based on the dataset retrieved from https://www.kaggle.com/datasets/prishasawhney/imdb-dataset-top-2000-movies

## Contributors
@Yeesbae -  <br />
@WeiHaoChin - EDA, Data Cleaning , Logistic Regression, Decision Tree, Slides , Video script <br />
@cherylchq - 
## Context and outline 
We chose to talk about this topic as understanding the factors that influence imdb ratings can allow us to gain deeper insights into the reasons behind film success and viewer preferences, and what attributes would make a film appeal more to its viewers <br/>

This can allow stakeholders to make more informed decisions in the cinema industry and even tailor marketing strategies to draw more viewer ratings and engagement. 


## Problem Definition

Are we able to predict if a movie is good (rating above 6) based on its attributes? <br />
Which model would be the best to predict it?

## Machine Learning algorithms used
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Conclusion
1. Metascore has the highest correlation with IMDB Ratings
3. Dataset is distributed unevenly and skewed towards higher IMDB Ratings
4. Model created using Decision tree has a high False Positive Rate
5. Model for Logistic Regression created using this data can only predict IMDB rating above 6 due to the dataset constraints.
6. Models are improved by using Multi variables to predict data, with Metascore being the most important variable

## What did we learn from this project
1. Alpha pruning for Decision Tree
2. Alpha pruning improves classification accuracy of test dataset
3. Able to discern unnecessary information given a pool of data <br/>
4. Understood machine learning models used (Regression Line,Decision Tree) <br/>
5. Understood Random forest model <br/>
6. Convert text to weighted numerical representations <br/>
7. Learnt to use github efficiently for group work


## Credit for data
For the data set that we used, it was from Kaggle: https://www.kaggle.com/datasets/prishasawhney/imdb-dataset-top-2000-movies

## References 
https://www.youtube.com/watch?v=q90UDEgYqeI
https://scikit-learn.org/0.24/modules/generated/sklearn.metrics.plot_confusion_matrix.html
