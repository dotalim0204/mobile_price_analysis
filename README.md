# Welcome to mobile_price_analysis repository

![image](https://user-images.githubusercontent.com/50509341/163121347-e1b45718-4e46-417e-8f01-5ed60a8bf1eb.png)

## Problem Definition
How to predict mobile price using given features? Besides, which model would be the best to solve this problem?

## About

This is a Mini Project for SC1015 which focuses on mobile price from [Kaggle by manishkc06](https://www.kaggle.com/datasets/manishkc06/mobile-price-prediction). For detailed walkthrough, please view the source code in order from:

1. [Data Preprocessing](Data%20Preprocessing.ipynb) <br>As the raw dataset was extremely messy, we learnt and used Regular Expression to format and clean the data, split several columns which contained too much information and corrected errors that were made during the cleaning process. More details in the notebook.<br><br>
2. [Data Visualization](Exploratory%20Data%20Analysis.ipynb) <br>Used seaborn and matplotlib as our visualization tools. We explored each variable individually and found some variables with extreme values or null values. Besides, we also discovered the relationships of those variables with respect to mobile price, and we found out that for categorical variables, although their relationships with mobile price might be implicit, but they became explicit if we partition them in a different way. We also explored the relationships of different variables other than mobile price, observed some characteristics and patterns of different mobile brands and derived some data driven insights. More details in the notebook.<br><br>
3. [Feature Engineering](Feature%20Engineering.ipynb) <br> We removed some useless variables, such as those categorical variables that contained only 1 category. During the EDA process, we found some data have extremely high depth, we proceeded to remove them in feature engineering. In order to fit the data into our model, we used one-hot encoding for both nominal and ordinal categorical variables. Lastly, we rearranged the columns. More details in the notebook.<br><br>
4. [Machine Learning](Machine%20Learning.ipynb) <br> Used Linear Regression, Random Forest Regressor & GridsearchCV as our tools. Linear Regression is simplier compared to other methods. For Random Forest Regressor, we used trial and error to find the seemingly best hyperparameter. Although running GridSearchCV took us a lot of time, we achieved the best performance by using this method. We compared the performance of the model by using R^2 (higher better) and MSE (lower better) as our metrics, and plotted the graph of Predicted Value against True Value to see whether the dots fit well on the line. We also did the machine learning process twice, using the dataset before and after feature selection, and compared the changes in performance. More details in the notebook.

### Datasets Folder
Contains three datasets used in this project

1. mobile_data_data.csv - Raw dataset from kaggle
2. mobile_data_new.csv - Dataset after Pre-processing and used for EDA
3. mobile_price_final.csv - Dataset after Feature Engineering and used for Machine Learning

### Slides Folder
Contains the powerpoint slides which provide a quick summary of our project. It covers our practical motivation for this project, the overall aim, data extraction and preparation, our analysis on the data and some justifications, feature engineering, machine learning using different models, data driven insights, as well as the conclusions and recommendations we draw from our work.

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

## What did we learn from this project?

- Handling messy dataset
- Fully utilize Regular Expression to clean and format our data
- Analyze the variables and their relationships from graph
- Characteristics of different brands of mobile phones
- How to work on GitHub
- One-hot encoding for both ordinal and nominal variables
- Random Forest Regressor and GridSearchCV from sklearn

## Conclusion

- Specs related to running speed (Ram Size, GPU Speed, etc.) are usually the most important factors in predicting mobile price
- Some mobile brands have low specs but higher prices, perhaps it is due to their popularity
- Linear Regression isn't really useful especially after feature selection
- GridSearchCV is able to find the best hyperparameter for Random Forest Regressor in a more systematic way, which results in the best performance
- It is possible to predict mobile price using the features in our dataset
- In the future, we may add more features, such as prioritise smartphone features according to lifestyle choices, or recommend popular phone models for users with similar needs

## Contributors

- @dotalim0204 (Lim Jun Hern, U2120981B) - Data Preprocessing, Feature Engineering, Machine Learning, Slides, Script
- @HLeong12345 (Leong Hong Yi, U2120932C) - Data Visualization, Slides, Script
- @limweilun (Lim Wei Lun, U2120218G) - Machine Learning, Slides, Script, Video

## References
- <https://slidesgo.com/theme/electronic-circuit-style-cv>
- <https://www.kaggle.com/datasets/manishkc06/mobile-price-prediction>
- <https://www.statista.com/statistics/494598/smartphone-users-in-singapore/>
- <https://scikit-learn.org/stable/modules/model_evaluation.html/>
- <https://www.xe.com/currencyconverter/convert/?Amount=1&From=INR&To=SGD>
- <https://machinelearningmastery.com/how-to-one-hot-encode-sequence-data-in-python/>
- <https://vitalflux.com/mean-square-error-r-squared-which-one-to-use/>
