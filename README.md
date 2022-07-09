
# PIMA-Indian-Diabetes-Dataset

![medicine-doctor-stethoscope-touching-medical-icons-network-medicine-doctor-stethoscope-touching-icons-medical-network-111489030](https://user-images.githubusercontent.com/70154122/175789777-732ed156-217e-417d-b016-a6a044dc498d.jpg)

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
## Content
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
## Problem Statement:
Build a model to accurately predict whether the patients in the dataset have diabetes or not. The datasets consists of several medical predictor variables and one target variable, Outcome. Pregnancies: Number of times pregnant Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test BloodPressure: Diastolic blood pressure (mm Hg) SkinThickness: Triceps skin fold thickness (mm) Insulin: 2-Hour serum insulin (mu U/ml) BMI: Body mass index (weight in kg/(height in m)^2) DiabetesPedigreeFunction: Diabetes pedigree function Age: Age (years) Outcome: Class variable (0 or 1) 268 of 768 are 1, the others are 0
## Contribution towards the project:
The objective is to find a model which will be able to predict whether a person is likely to have diabetes or not given their medical records. Various statistical models was tested against this dataset to find the one which will be best suited for this problem. This project also aimed to understand which features are significant to correctly predict whether a person is havind diabetes or not. 
## Methodology
The dataset was cleaned before analysis as this dataset contained missing values. Following that outliers were also treated that was present in the dataset. 
Exploratory data analysis was conducted on this dataset to get a better understanding of the data. Due to the small size of the dataset, statistical models are used mostly for this dataset and to compare machine learning model is also used. This dataset was a unbalance dataset and thus SMOTE was used to balance the dataset and again use models to find which best suits this dataset.
## Models Used:
1) KNN
2) Linear Discriminant Analysis
3) Quadratic Discriminant Analysis
4) Logistic Regression
5) Xg Boost
## Notebook Used
Python Notebook used with version 3.9.7 in jupyter.
## Library Used
1) pandas
2) numpy
3) seaborn
4) sklearn
5) matplotlib
6) xgboost
7) statsmodels.api

## Screenshots
![Pima_1](https://user-images.githubusercontent.com/70154122/175788579-5eea41db-6946-4dd9-b82d-e41cbe946333.jpg)
![Pima_2](https://user-images.githubusercontent.com/70154122/175788592-95f4b388-06df-47d0-ad4a-f76f92e3ff51.jpg)
![Pima_3](https://user-images.githubusercontent.com/70154122/175788595-8ad5fd99-a29c-43e2-8c5f-9c1908b51d19.jpg)


## Conclusion
Without smote the best model is KNN with an accuracy of 79% and also the AUC-ROC score, after implementing SMOTE can see that KNN has the best accuracy at 83% but the AUC-ROC score for LDA is the highest. I choose KNN over LDA as its errors which are False Positive(FP) & False Negative(FN) are low compared to LDA.
Thus, it being a healthcare problem we should try to choose a model whose not only accuracy-wise good but also False Positive(FP) & False Negative(FN) are low and hence KNN is a better model.

The Power BI visualization is attached.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/joyb05)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joy-bhowmick-37269b80/)




