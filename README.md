# Cardio-Vascular-Disease-Risk-Prediction.
Table of Contents
* About the Project
  * Overview
  * Built With
  * Dataset
  * Results
  * License
  
* Overview

## ABSTRACT :
Cardiovascular disease is one of the most heinous diseases, especially the silent
heart attack, which attacks a person so abruptly that there's no time to get it treated
and such disease is very difficult to be diagnosed. Various medical data mining and
machine learning techniques are being implemented to extract the valuable
information regarding the heart disease prediction. Yet, the accuracy of the desired
results are not satisfactory. This Model proposes a heart disease prediction system
using Machine learning techniques. Health care field has a vast amount of data, for
processing those data certain techniques are used. Data Mining Is one of the
techniques often used. Heart diseases are the Leading cause of death worldwide.
This System predicts the arising possibilities of Heart Disease. The datasets used
are classified in terms of medical parameters. This system evaluates those
parameters using data mining classification technique. The datasets are processed
in python programming using five main Machine Learning Algorithms namely
Decision tree Algorithm and Naive Bayes Algorithm, Linear Regression, Knn
Algorithm, Artificial Neural Networking which shows the best algorithm among
these two in terms of accuracy level of heart disease.

 ## INTRODUCTION :
 According to the World Health Organisation, every year 12 million deaths
occur worldwide due to Heart Disease. Heart disease is one of the biggest causes of
morbidity and mortality among the population of the world. Prediction of
cardiovascular disease is regarded as one of the most important subjects in the
section of data analysis. The load of cardiovascular disease is rapidly increasing all
over the world from the past few years. Many researches have been conducted in
an attempt to pinpoint the most influential factors of heart disease as well as
accurately predict the overall risk. Heart Disease is even highlighted as a silent
killer which leads to the death of the person without obvious symptoms. The early
diagnosis of heart disease plays a vital role in making decisions on lifestyle
changes in high-risk patients and in turn reduces the complications.
Machine learning proves to be effective in assisting in making decisions and
predictions from the large quantity of data produced by the healthcare industry.
This project aims to predict future Heart Disease by analysing data of patients
which classifies whether they have heart disease or not using a machine-learning
algorithm. Machine Learning techniques can be a boon in this regard. Even though
heart disease can occur in different forms, there is a common set of core risk
factors that influence whether someone will ultimately be at risk for heart disease
or not. By collecting the data from various sources, classifying them under suitable
headings & finally analysing to extract the desired data we can say that this
technique can be very well adapted to do the prediction of heart disease

## MOTIVATION FOR THE WORK :
The main motivation of doing this research is to present a heart disease
prediction model for the prediction of occurrence of heart disease. Further, this
research work is aimed towards identifying the best classification algorithm for
identifying the possibility of heart disease in a patient. This work is justified by
performing a comparative study and analysis using three classification algorithms
namely Naïve Bayes, Decision Tree, and Random Forest are used at different levels
of evaluations. Although these are commonly used machine learning algorithms,
the heart disease prediction is a vital task involving highest possible accuracy.
Hence, the three algorithms are evaluated at numerous levels and types of
evaluation strategies. This will provide researchers and medical practitioners to
establish a better

# PROBLEM STATEMENT :
Detecting heart disease presents a significant challenge, as current diagnostic tools are either too costly or insufficiently effective at accurately predicting the likelihood of heart disease in individuals. Early identification is crucial in reducing mortality rates and minimizing complications. However, consistently monitoring patients is not feasible, as it demands substantial time, effort, and expertise from healthcare professionals, making round-the-clock consultation impractical. In today’s data-driven world, machine learning algorithms provide a viable alternative. By analyzing large datasets, these algorithms can uncover hidden patterns, offering valuable insights for medical diagnoses and improving the accuracy of heart disease predictions.


## Built With :
The working of the system starts with the collection of data and selecting
the important attributes. Then the required data is preprocessed into the required
format. The data is then divided into two parts: training and testing data. The
algorithms are applied and the model is trained using the training data. The
accuracy of the system is obtained by testing the system using the testing data. This
system is implemented using the following modules.
1.) Collection of Dataset
2.) Selection of attributes
3.) Data Preprocessing
4.) Balancing of Data
5.) Disease Prediction

# Dataset

  * Source : https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
  Each data-set consisted of 14 attributes.
  Moreover, it is recommended to use only 14 for our analysis & later we will find out that only 6 attributes have a significant effect.
  In addition to this, heart-disease prediction is carried out using Logistic Regression Model, Multinomial Naive Bayes Model, Decision Tree Model, K-Nearest Neighbour and Artificial Neural Network .
 * Attribute Information:-
1) age
2) sex
3) chest pain type (4 values)
4) resting blood pressure
5) serum cholestoral in mg/dl
6) fasting blood sugar > 120 mg/dl
7) resting electrocardiographic results (values 0,1,2)
8) maximum heart rate achieved
9) exercise induced angina
10) oldpeak = ST depression induced by exercise relative to rest
11) the slope of the peak exercise ST segment
12) number of major vessels (0-3) colored by flourosopy
13) thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

# Results 
1) Linear Regression Model
   * Accuracy(%) : 76.92
   * Sensitivity(%) : 68.51
   * Specificity(%) : 89.18
   
   
   ![image](https://user-images.githubusercontent.com/108573409/211609157-e0f7ef7e-163d-4411-b7a5-12ac8fe865ca.png)

2) Multinomial Naive Bayes Model
   * Accuracy(%) : 73.77
   * Sensitivity(%) : 77.41
   * Specificity(%) : 70.0


   ![image](https://user-images.githubusercontent.com/108573409/211609217-3047edb4-ac20-423f-b08e-ee9ec4567b8d.png)

3) Decision Tree Model
   * Accuracy(%) : 78.02
   * Sensitivity(%) : 69.09
   * Specificity(%) : 91.66


   ![image](https://user-images.githubusercontent.com/108573409/211609285-a7b82f4c-622b-4d97-b8c2-a824396a11b4.png)

4) K-Nearest Neighbour Model
   * Accuracy(%) : 82.41
   * Sensitivity(%) : 75.51
   * Specificity(%) : 90.47


   ![image](https://user-images.githubusercontent.com/108573409/211609321-9e5938d7-90fe-4a77-bd0a-1b6d8794a995.png)

5) Artificial Neural Network Model
   * Accuracy(%) : 83.51
   * Sensitivity(%) : 90.0
   * Specificity(%) : 91.46 


![image](https://user-images.githubusercontent.com/108573409/211609368-d026ad99-9715-455e-bbbd-9fb35ae6a344.png)

# License
Distributed under the MIT License. See LICENSE for more information.
