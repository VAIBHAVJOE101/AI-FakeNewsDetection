# **Fake News Detection**
## **Overview**
---
Nowadays social-networking systems, online news portals, and other online media have become the main sources of news through which interesting and breaking news are shared at a rapid pace. However, many news portals serve special interest by feeding with distorted, partially correct, and sometimes imaginary news that is likely to attract the attention of a target group of people. Fake
news has become a major concern for being destructive sometimes spreading confusion and deliberate disinformation among the people.

The Aim of this projects is to use  Machine learning  to detect the Fake news based on the text content of the Article.And after building the suitable Machine learning model to detect the fake/true news .


## **Dataset**
Dataset that used in this project are collected from Kaggle (https://www.kaggle.com/).
https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

There are two files, one for real news and one for fake news with a total of 23481 "fake" articles and 21417 "real" articles.

## **Data preprocessing**
---
1. Remove all unwanted columns.
2. Remove All Missing Values Records.
3. Removing all the extra information like brackets, any kind of puctuations - commas, apostrophes, quotes, question marks from Text.
4. Remove all the numeric text, urls from Text.
5. Remove all stopwords from Text like is , the ,of ,etc .


## **ML model Traning and Building**
---
Here we have build all the classifiers for predicting the fake news detection. The extracted features are fed into different classifiers. We have used Logistic Regression  ,Random forest and   DecisionTree classifier . Each of the extracted features were used in all of the classifiers. Once fitting the model, we compared the accuracy score and checked the confusion matrix.


## Comparing Accuracies of Models

| Model                     | Accuracy     |
|:-------------------------:|:------------:|
| Logistic Regression       | 99.01%       |
| Decision Tree Classifier  | 99.64%       |
| Random Forest Classifier  | 98.94%       |


