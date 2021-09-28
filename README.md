# Personalised-Cancer-Diagnosis
Classification of genetic variations/mutations based on evidence from text-based clinical literature. It is a multi class classification problem in which a genetic mutation can be classified into nine different classes. Multi class logloss performance metric is used and log-loss is found for different Machine Learning algorithm. So the probability of each data point is to be predicted which belongs to each of the nine classes.
# Business Problem Description
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

List item
List item
Data: Memorial Sloan Kettering Cancer Center (MSKCC)

Download training_variants.zip and training_text.zip from Kaggle.

Context:
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.
# Real-world/Business objectives and constraints.
1-No low-latency requirement.
2-Interpretability is important.
3-Errors can be very costly.
4-Probability of a data-point belonging to each class is needed.

# Data Overview
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID
Data file's information:
1-training_variants (ID , Gene, Variations, Class)
2-training_text (ID, Text)
# Performance Metric
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment#evaluation

Metric(s):
 1-Multi class log-loss
 2-Confusion matrix
 
 # Objectives and Constraints
 
Objective: Predict the probability of each data-point belonging to each of the nine classes.
Constraints:
* Interpretability * Class probabilities are needed. * Penalize the errors in class probabilites => Metric is Log-loss. * No Latency constraints.
