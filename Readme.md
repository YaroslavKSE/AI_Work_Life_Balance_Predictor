# Work-Life Balance Prediction Model

## Overview
This repository contains the Jupyter Notebook (`AI_Project_KSE_WorkLifeBalance.ipynb`) and a PDF document (`Work-Life_Balance_Improvement_Strategies.pdf`) detailing strategies to improve work-life balance based on our findings using machine learning techniques. The main goal of this project is to use lifestyle data to predict work-life balance scores and derive actionable insights to improve daily life.

## Contents
- `AI_Project_KSE_WorkLifeBalance.ipynb`: A Jupyter Notebook that outlines the entire machine learning pipeline, from data cleaning to model training. The notebook utilizes XGBoost, a powerful machine learning algorithm, to predict work-life balance scores.
- `Work-Life_Balance_Improvement_Strategies.pdf`: A document providing recommendations derived from the model's feature importance analysis. These recommendations aim to help individuals enhance their work-life balance based on predictive insights.
- `Wellbeing_and_lifestyle_data_Kaggle.сім`: A dataset used for training the model.
- `Survey_responses.csv`: A dataset which contains responses from our survey which we have conducted in order to test the model.

## Notebook Details
### Data Cleaning
The notebook begins with the data cleaning process where raw data is transformed into a clean dataset ready for analysis. This includes handling missing values, encoding categorical variables, and normalizing data.

### Model Building
The cleaned data is then used to build a predictive model. We employ the XGBoost algorithm due to its efficiency and accuracy. The model's performance is evaluated using metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error), achieving an R-squared value of 99.9999992%, which indicates an excellent fit.

## Recommendations Document
The PDF document outlines various strategies that individuals can adopt to improve their work-life balance. These strategies are based on key features identified by the XGBoost model as significant predictors of work-life balance. Recommendations include lifestyle adjustments like increasing fruit and vegetable intake, reducing stress, and engaging more with community and social networks.

## Conclusion
This project not only showcases the application of advanced machine learning techniques but also provides practical solutions that can be implemented in everyday life to achieve better work-life balance. The combination of predictive analytics and actionable insights offers a unique approach to personal well-being improvement.
