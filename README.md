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
Cardiovascular disease, particularly the silent heart attack, is one of the most dangerous conditions, as it strikes suddenly, leaving little time for treatment and making it highly difficult to diagnose. To improve heart disease prediction, various machine learning and medical data mining techniques have been employed to extract valuable insights, though the accuracy of these methods has yet to meet expectations. This model introduces a heart disease prediction system utilizing machine learning techniques. The healthcare sector generates vast amounts of data, and processing this data requires specialized methods, with data mining being one of the most commonly used techniques. Heart disease remains the leading cause of death globally. This system predicts potential heart disease risks by analyzing medical datasets categorized by specific parameters. These parameters are evaluated through data mining classification techniques. Using Python, the model processes these datasets with five key machine learning algorithms: Decision Tree, Naive Bayes, Linear Regression, K-Nearest Neighbors (KNN), and Artificial Neural Networks. The model ultimately determines which algorithm yields the highest accuracy in predicting heart disease.

 ## INTRODUCTION :
According to the World Health Organization, heart disease causes approximately 12 million deaths annually worldwide, making it one of the leading contributors to global morbidity and mortality. Predicting cardiovascular disease has become a critical focus in data analysis, as the burden of this disease has been rising rapidly in recent years. Numerous studies have attempted to identify the key risk factors for heart disease and improve the accuracy of predicting overall risk. Often referred to as a "silent killer," heart disease can lead to death without showing obvious symptoms. Early detection is crucial for implementing lifestyle changes in high-risk patients, ultimately reducing complications.

Machine learning has proven to be an effective tool for making predictions and supporting decisions based on the vast amounts of data generated in the healthcare industry. This project aims to predict the likelihood of heart disease in patients by analyzing their data and using machine learning algorithms to classify whether they are at risk. Although heart disease manifests in various forms, a common set of risk factors consistently influences an individual's risk. By collecting data from multiple sources, categorizing it appropriately, and analyzing it to extract meaningful insights, machine learning can play a vital role in predicting heart disease and improving early diagnosis.

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
