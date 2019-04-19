# Human-Acivity-Recognition
This project is to build a model that predicts the human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying.

## Problem Statement:
Given a new datapoint we have to predict the Activity

## Dataset:
Dataset is taken from http://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones.

## Exploaratory Data Analysis:
1) Data Cleaning:
-Check for duplicates and nan values.Check for data imbalance to plot data provided by each user. 
2) EDA
PLot for
-Stationary and Moving activities are completely different
-Magnitude of an acceleration can saperate it well
-Plot tsne plot with different perplexities.

## Prediction models:
Train different machine learning models on data
1) Logistic regression
2) Linear SVC
3) Kernel SVM
4) Decision Trees
5) Random Forest Classifier
6) GBDT
Get more accuracy with Linear SVC i.e 96.61%

## LSTM:
-Defined 1 layer and 2 layer LSTM architecture and got 93.25% accuracy with 2 layer architecure.

