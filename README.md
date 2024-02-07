## Final Project - Toxic Player Validator

* Authors: Amara Tariq and Steven Kim
* Class: Natural Language Processing Sp22

## Overview

This program takes in a dataset (found here: https://www.kaggle.com/datasets/simshengxue/league-of-legends-tribunal-chatlogs) of League of Legends chatlogs and runs various text processing steps along with running BERT model and sentiment analysis on the dataset. 

## Manifest

* README.md - Brief description of project and run instructions
* Logistic Regression & BERT testing.ipynb - looks at the logistic regression of TFIDF vectorizor and tests using BERT
* VADER_Dataframe.ipynb - creates dataframe using VADER sentiment analysis values
* Remove_enemy_Dataframe.ipynb - removes messages from dataframe in order to view in the offenders point of view
* Detoxify_Dataframe.ipynb - Adds detoxify values to the VADER dataframe
* Language_Dataframe.ipynb - creates the language values using the spacy language detection
* BERT.ipynb - loops through three different report reasons dataframes and calculates accuracy
* SVM(sentiment_scores, toxicity).ipynb - calculates the accuracy using support vector machines and logistic regression
* chatlogs.csv - overall csv file 

## Building the project

Any code files and .csv files that are needed to run this project can be found in a Google Drive folder found here: https://drive.google.com/drive/folders/1fv6UHg5YVIp9W8BKtKO4Jv5vH6I5GMSY?usp=sharing/

Note to alter any pathing in all files to where you have installed all the files. 

Order to run files:
* Language_Dataframe.ipynb
* Remove_enemy_dataframe.ipynb
* VADER_Dataframe.ipynb
* Detoxify_Dataframe.ipynb


The remaining files can be run in any order, as they are not dependent on one another, they are simply dependent on the Dataframes and CSV files created from the above files. 

Note: We have included all 'pip install' commands as well.