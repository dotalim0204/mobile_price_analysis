# Welcome to mobile_price_analysis repository

![image](https://user-images.githubusercontent.com/50509341/163121347-e1b45718-4e46-417e-8f01-5ed60a8bf1eb.png)

## About

This is a Mini Project for SC1015 which focuses on mobile price from [Kaggle by manishkc06](https://www.kaggle.com/datasets/manishkc06/mobile-price-prediction). For detailed walkthrough, please view the source code in order from:

1. [Data Preprocessing](Data%20Preprocessing.ipynb)
2. [Data Visualization](Exploratory%20Data%20Analysis.ipynb)
3. [Feature Engineering](Feature%20Engineering.ipynb)
4. [Machine Learning](Machine%20Learning.ipynb)

## Contributors

- @dotalim0204 (U2120981B) - Data Preprocessing, Feature Engineering, Machine Learning, Slides, Script
- @HLeong12345 () - Data Visualization, Slides, Script
- @limweilun (U2120218G) - Machine Learning, Slides, Script, Video

## Tech Stack

## Files Explaination? 

## Libraries

- Pandas
- RegEx
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Models Used

1. Linear Regression
2. Random Forest Regressor
3. GridSearchCV

## Problem Definition

- How to predict mobile price using given features?
- Which model would be the best to solve this problem?


## What did we learn from this project?

- Handling messy dataset
- Fully utilize Regular Expression to clean and format our data
- Characteristics of different brands of mobile phones
- One-hot encoding for both ordinal and nominal variables
- RandomForestRegressor and GridSearchCV from sklearn
- Collaborating using GitHub

## Conclusion

- Speeds (Ram Size, GPU Speed, etc.) are usually the most important factors for mobile price
- Some mobile brands have low specs but higher prices, perhaps those brands are more popular
- Linear Regression isn't really useful
- We are able to predict the mobile price accurately with less variables using RandomForestRegressor and GridSearchCV, but not Linear Regression
- GridSearchCV is able to find the best hyperparameter for RandomForestRegressor, results in highest accuracy
- It is possible to predict mobile price when given sufficient enough features

## References
- <https://slidesgo.com/theme/electronic-circuit-style-cv>
- <https://www.kaggle.com/datasets/manishkc06/mobile-price-prediction>
- <https://www.statista.com/statistics/494598/smartphone-users-in-singapore/>
- <https://scikit-learn.org/stable/modules/model_evaluation.html/>
- <https://www.xe.com/currencyconverter/convert/?Amount=1&From=INR&To=SGD>
- <https://machinelearningmastery.com/how-to-one-hot-encode-sequence-data-in-python/>
- <https://vitalflux.com/mean-square-error-r-squared-which-one-to-use/>
