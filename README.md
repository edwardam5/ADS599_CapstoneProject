# How Machine Learning can aid Doctors in Predicting and Preventing Heart Disease
<p align="center">
A Predictive Analysis of Heart Disease through Classification Modeling 
</p>

<p align="center">
<img width="322" alt="Screen Shot 2023-08-04 at 9 12 16 AM" src="https://github.com/edwardam5/ADS599_CapstoneProject/assets/107288109/680b8da2-4849-499f-b44d-ddda17851e30">
</p>

## Installation Directions 
Download the project code from this GitHub repository and run cells. This can be accomplished by cloning the repository onto your device using the commands below: 
* ```git init```
* ```git clone https://github.com/edwardam5/ADS599_CapstoneProject.git``` 

## Contributors
Saba Alemayehu and Anusia Edward

## Abstract 
The purpose of this study is to aid health care professionals, such as doctors and nurses, to identify at-risk patients in order to provide prevention methods needed to help their patients be proactive with managing their health. In order for this to be carried out the following seven machine learning algorithms were built: Logistic Regression, Neural Network, Random Forest, Linear Discriminant Analysis, Naive Bayes, K-Nearest Neighbor, and Decision Tree. The model that produced the best results was noted to be the Logistic Regression model with an accuracy of 92% and an AUC score of 0.84. The seven models can be ranked as follows from greatest predictability to least predictability: Logistic Regression, Neural Network, Random Forest, Linear Discriminant Analysis, Naive Bayes, K-Nearest Neighbor, and Decision Tree. The top three indicators of the Logistic Regression model were found to be general health, age, and history of strokes. Future studies can expand on the current research through the expansion of the research length to include longitudinal data. 

## Table of Contents
* [Business Background](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#business-background)
* [Problem Statement](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#problem-statement)
* [Summary of Findings](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#summary-of-findings) 
* [Business Question](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#business-question)
* [Approach](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#approach) 
* [Limitations](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#limitations) 
* [Call to Action](https://github.com/edwardam5/ADS599_CapstoneProject/tree/main#call-to-action) 

## Business Background
Heart disease claims approximately 17.9 million lives worldwide (World Health Organization: WHO, 2019). On a national level, roughly 2,000 people die in the United States each day from this disease (Heart Disease and Stroke Statistics - 2020 Update, n.d.). Heart disease can be attributed to a variety of factors including smoking, alcoholism, poor dietary choices, and lack of exercise (CDC Heart Disease Facts, 2023). Common biomarkers that indicate the risk of heart disease include cholesterol and blood pressure values. Heart disease encompasses different types of diseases affecting the heart such as heart attacks and coronary artery disease. As one of the leading causes of death in the United States, it is imperative that measures are taken to identify and reduce the prevalence of these deaths among at-risk populations (CDC Heart Disease Facts, 2023). 

## Problem Statement
Prevention of heart disease is much more effective in extending the life of individuals than treating heart disease. Taking steps to identify at-risk patients is imperative to combat this leading cause of death. Overall, it can be noted that heart disease is consuming the lives of many individuals around the world. This fact is a source of motivation for pursuing this topic for our study. Analyzing the statistics in regards to heart disease has shown a need for analysis. Keeping this in mind, we were motivated to explore this topic further by utilizing machine learning algorithms.

## Summary of Findings 
Seven machine learning models were built to help doctors identify at-risk patients in order to provide prevention methods needed to help their patients be proactive with managing their health. Based on the seven models produced, it can be noted that the model that outperformed all other models was determined to be the Logistic Regression model. The seven models can be ranked as follows from greatest predictability to least predictability: Logistic Regression, Neural Network, Random Forest, Linear Discriminant Analysis, Naive Bayes, K-Nearest Neighbor, and Decision Tree. It should be noted that all models performed with an accuracy greater than 85%, and therefore are all somewhat sufficient models that can be further expanded on and employed. The three key attributes that were noted based on the best model, the Logistic Regression model, are as follows: general health, age, and history of strokes. The ranking of comorbidities and other health related factors can be noted as follows: history of strokes, sex, diabetes, kidney disease, race, smoking, alcohol drinking, skin cancer, sleep patterns, and mental health.

## Business Question
How can the implementation of data science, in terms of machine learning algorithms, impact the ongoing efforts to prevent incidence by heart disease? 

## Approach 
### Methods  
* Pre-processing 
* Data Visualization
* Data Exploration 
* Machine Learning Modeling
* Evaluation Metrics 
### Algorithms 
* Logistic Regression
* Neural Network
* Random Forest
* Linear Discriminant Analysis
* Naive Bayes
* K-Nearest Neighbor
* Decision Tree
### Technologies 
* GoogleColab - Python 
* Excel 
* GoogleDocs
 
## Limitations 
Some potential limitations of this study that should be considered are as follows: data biases and time constraints. The data obtained for this research project was through a survey-response style, which may indicate that there are some biases that influenced the model estimates as some of the data is subjective. Additionally, since the data was obtained through a volunteer basis, this may have resulted in a limited ability to properly assess the general public. In terms of time as a limitation factor, there was a time constraint on the research project (seven weeks); therefore, a longitudinal approach to this research study was not possible. More time and access to longitudinal data may have better aided with the overall predictability of heart disease.

## Call to Action 
In the future, the study can expand on the current research through a few different methods. First, the Logistic Regression model can be retested in order to find ways in which it can be improved in order to better predict heart disease. Also, in the future the impact of each of the attributes could also be further investigated. Subgroup analyses could additionally be conducted on the data to further determine new insights. An example of a subgroup analysis that could further the knowledge gained in this study would be to subset the information by race, sex, or age. These facets of the study may introduce interesting insights. Additionally, considering that the findings of this study contradict that of the 2013 study published under the title ‘Classification of heart disease using k-nearest neighbor and genetic algorithm’, continuous research into the performance of KNN in relation to other classification models can be explored to expand on the current research. Furthermore, additional research could be conducted to further verify the results obtained in this study in relation to the previous study. In the future, researchers should also consider including additional demographic attributes such as socioeconomic status, financial burdens, place of residence, occupation, and educational level to expand on knowledge of social factors in relation to heart disease. Another addition to the data that could aid with improving this study would be the inclusion of longitudinal data. Longitudinal data may better help with predicting whether or not individuals are at risk for heart disease. 
