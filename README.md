# Forecasting Amount Spent
![image](https://user-images.githubusercontent.com/73708363/215192643-805b5ade-9dc9-4c9f-a715-7af21ee9f806.png)

## Project Motivation
Forecasting is crucial for organizing marketing campaigns. What location or age group is needed to put more emphasis, to what type of offer the population will respond better, and how much will the earnings will be are some of the problems that Marketing needs to face.

For all these tasks a prediction model is indispensable. In this respect, well-known is the Random Forest model and its forecasting capacity; so using a mimic data set of Starbucks users, this model was implemented and tuned to help Starbucks know how much someone will spend based on demographics and offer type.

## Blog 
A blog with the explanation of each of the steps can be found in the following link: https://medium.com/@eparedes90/forecasting-amount-spent-by-starbucks-user-fa57fddd8080

As conclusion the blog explained that it was possible to build a supervised regression model that can predict the amount by the user based on demographics and offer type, after data cleaning, removing outliers, transforming variables into dummies.
The model indicated, at first, an overfitting situation, which was solved with the use of Hyperparameter tunning and the RandomSearchCV command to find the best parameter. After hyperparameter tunning the prediction accuracy increased by 4.4%.

## Content

1. data
- portfolio.json #Characteristics of each offer
- profile.json #Characteristics of each user
- transcript.json #Transactions

2. Project.ipynb #Jupyter Notebook

3. df_clean.pkl #data after wrangling

4. README.md

5. Requirements.txt #List of libraries and versions

6. .venv #virtual environment

7. .vscode #Visual Studio configuration of json

8. Random Forest Regressor object #fit after tunning

## Instructions
1. Open Project.ipynb and run the file
2. Install all the libraries and its version from requirements.txt
3. To avoid running all the steps (and save time) in Project.ipynb there are checkpoints. For example, the code for opening df_clean.pk (line 28).

## Acknowledgments
1. Starbucks mimic data set given by Udacity
2. https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74 #Code used for Tunning Random Forest Regressor
3. https://www.analyticsvidhya.com/blog/2021/05/know-the-best-evaluation-metrics-for-your-regression-model/ #Metrics for model evaluation)
4. Photo by Niels Kehl on Unsplash

