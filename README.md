# Obesity Prediction

This repository contains a data science project on a dataset from Palechor & Manatos (2019). It contains information about the lifestyle and physical attributes of 2111 individuals from Peru, Colombia and Mexico, with a total of 17 features/variables measured. One of these variables is Weight status ("Obesity" column). My goal in this project was to fit a machine learning model to this dataset to predict weight status using the other variables provided in this dataset. I accessed this dataset and conducted the analysis on Kaggle. The link to the dataset is here: [Kaggle dataset](https://www.kaggle.com/datasets/ruchikakumbhar/obesity-prediction/code). 

Below is a table describing the variables measured: 


| Variable name  |                    Question asked                    |                      Options                      |
|----------------|------------------------------------------------------|---------------------------------------------------|
|     Gender     |                 What is your gender?                 |                    Male, Female                   |
|      Age       |                  What is your age?                   |                   Numeric value                   |
|     Height     |                 What is your height?                 |              Numeric value in meters              |
|     Weight     |                 What is your weight?                 |                Numeric value in kg                |
| family_history | Has a family member suffered/suffer from overweight? |                      No, Yes                      |
|      FAVC      |       Do you eat high caloric food frequently?       |                      No, Yes                      |
|      FCVC      |     Do you usually eat vegetables in your meals?     |              Never, Sometimes, Always             |
|      NCP       |        How many main meals do you have daily?        |                     1-2, 3, >3                    |
|      CAEC      |          Do you eat any food between meals?          |         No, Sometimes, Frequently, Always         |
|     SMOKE      |                    Do you smoke?                     |                      No, Yes                      |
|      CH2O      |          How much water do you drink daily?          |                   <1L, 1-2L, >2L                  |
|      SCC       |      Do you monitor the calories you eat daily?      |                      No, Yes                      |
|      FAF       |       How often do you have physical activity?       |        Never, 1-2 days, 2-4 days, 4-5 days        |
|      TUE       |   How much time do you use technological devices?    |           0-2 hours, 3-5 hours, >5 hours          |
|      CALC      |           How often do you drink alcohol?            |        Never, Sometimes, Frequently, Always       |
|     MTRANS     |           Which transportation do you use?           |       Walking, Bike, Public transportation, Motorbike, Automobile |
|    Obesity     |               Category of body weight                | Underweight, Normal, Overweight I, Overweight II, Obesity I, Obesity II, Obesity III |


I focused on fitting the random forest classifier and multinomial logistic regression for this dataset. The notebook contain my work is here: [obesity-prediction.ipynb](https://github.com/layaasiv/obesity-prediction/blob/main/obesity-prediction.ipynb) 
