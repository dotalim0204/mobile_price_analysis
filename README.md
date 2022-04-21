# Welcome to mobile_price_analysis repository

![image](https://user-images.githubusercontent.com/50509341/163121347-e1b45718-4e46-417e-8f01-5ed60a8bf1eb.png)

## About

This is a Mini Project for SC1015 which focuses on mobile price from [Kaggle by manishkc06](https://www.kaggle.com/datasets/manishkc06/mobile-price-prediction). For detailed walkthrough, please view the source code in order from:

1. [Data Preprocessing](Data%20Preprocessing.ipynb) <br>Used Regular Expression to format and clean the data, split several columns and corrected errors that were made during the cleaning process. More details in the notebook.<br><br>
2. [Data Visualization](Exploratory%20Data%20Analysis.ipynb) <br>Used seaborn and matplotlib as our visualization tools. Explored each variable individually, discovered their relationships with respect to mobile price, as well as observed some characteristics and patterns of different mobile brands. More details in the notebook.<br><br>
3. [Feature Engineering](Feature%20Engineering.ipynb) <br> Removed some useless variables (For example, categorical variables that contain only 1 category), and some extremely odd outliers after EDA. Used one-hot encoding on categorical variables in order to fit them into our models. More details in the notebook.<br><br>
4. [Machine Learning](Machine%20Learning.ipynb) <br> Used Linear Regression, Random Forest Regressor & GridsearchCV. For Random Forest Regressor, we used trial and error to find the seemingly best hyperparameter. For GridSearchCV, we used a more systematic way to find the optimal solution. Compared the performance of the model before and after feature selection, using R^2 and MSE as our metrics, and plot the graph of Predicted Value against True Value as well. More details in the notebook.

### Datasets Folder
Contains three datasets used in this project

1. mobile_data_data.csv - Raw dataset from kaggle
2. mobile_data_new.csv - Dataset after Pre-processing and used for EDA
3. mobile_price_final.csv - Dataset after Feature Engineering and used for Machine Learning

## Contributors

- @dotalim0204 (U2120981B) - Data Preprocessing, Feature Engineering, Machine Learning, Slides, Script
- @HLeong12345 (U2120932C) - Data Visualization, Slides, Script
- @limweilun (U2120218G) - Machine Learning, Slides, Script, Video

## Libraries

- Pandas
- RegEx
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Models Used

- Linear Regression
- Random Forest Regressor
- GridSearchCV

## Problem Definition

- How to predict mobile price using given features?
- Which model would be the best to solve this problem?


## What did we learn from this project?

- Handling messy dataset
- Fully utilize Regular Expression to clean and format our data
- Analyze the variables and their relationships from graph
- Characteristics of different brands of mobile phones
- One-hot encoding for both ordinal and nominal variables
- Random Forest Regressor and GridSearchCV from sklearn

## Conclusion

- Specs related to running speed (Ram Size, GPU Speed, etc.) are usually the most important factors in predicting mobile price
- Some mobile brands have low specs but higher prices, perhaps those brands are more popular
- Linear Regression isn't really useful to solve this problem
- We are able to predict the mobile price accurately with less variables using Random Forest Regressor and GridSearchCV, but not Linear Regression
- GridSearchCV is able to find the best hyperparameter for Random Forest Regressor, results in highest accuracy
- It is possible to predict mobile price when given sufficient enough features

## References
- <https://slidesgo.com/theme/electronic-circuit-style-cv>
- <https://www.kaggle.com/datasets/manishkc06/mobile-price-prediction>
- <https://www.statista.com/statistics/494598/smartphone-users-in-singapore/>
- <https://scikit-learn.org/stable/modules/model_evaluation.html/>
- <https://www.xe.com/currencyconverter/convert/?Amount=1&From=INR&To=SGD>
- <https://machinelearningmastery.com/how-to-one-hot-encode-sequence-data-in-python/>
- <https://vitalflux.com/mean-square-error-r-squared-which-one-to-use/>
