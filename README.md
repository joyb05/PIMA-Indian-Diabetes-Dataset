
# PIMA-Indian-Diabetes-Dataset

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
## Content
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
## Problem Statement:
Build a model to accurately predict whether the patients in the dataset have diabetes or not. The datasets consists of several medical predictor variables and one target variable, Outcome. Pregnancies: Number of times pregnant Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test BloodPressure: Diastolic blood pressure (mm Hg) SkinThickness: Triceps skin fold thickness (mm) Insulin: 2-Hour serum insulin (mu U/ml) BMI: Body mass index (weight in kg/(height in m)^2) DiabetesPedigreeFunction: Diabetes pedigree function Age: Age (years) Outcome: Class variable (0 or 1) 268 of 768 are 1, the others are 0
## Contribution towards the project:
The objective is to find a model which will be able to predict whether a person is likely to have diabetes or not given their medical records. Various statistical models was tested against this dataset to find the one which will be best suited for this problem. This project also aimed to understand which features are significant to correctly predict whether a person is havind diabetes or not. 
## Methodology
The dataset was cleaned before analysis as this dataset contained missing values. Following that outliers were also treated that was present in the dataset. 
Exploratory data analysis was conducted on this dataset to get a better understanding of the data. Due to the small size of the dataset, statistical models are used for the data and to compare one machine learning model is also used. 
## Models Used:
1) Linear Discriminant Analysis
2) Quadratic Discriminant Analysis
3) Logistic Regression
4) Xg Boost
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
![PairPlot](https://user-images.githubusercontent.com/70154122/172836931-ec5ff741-b35d-4775-ae8f-d202dbe56301.png)


## Conclusion
**Quadratic Discriminant Analysis** is giving the best result. **The accuracy was at 78%**, the model's **recall was 73% and precision was 85.3%** along with that it had the **lowest Type-I & Type-II error**, as this is a **healthcare domain problem** thus these errors should be the least. **Type-II error for this model is the least.** Therefore, this model is being chosen for the prediction of diabetes patients. **Glucose and BMI features** were the most significant in predicting whether a person has diabetes or not.
The Power BI visualization is attached.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/joyb05)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joy-bhowmick-37269b80/)




