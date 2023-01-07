# Countries-GDP-prediction 

#### Project Goal
The goal of the project is to understand this dataset, obtain valuable insights from it and finally to train a model that can predict the GDP per capita of a country. 

#### Data Source
We have the 'Countries of The World' data set 
(from kaggle: Fernando Lasso: https://www.kaggle.com/fernandol/countries-of-the-world).

#### Data Description
This dataset has every country as a data point (227 countries in total) and for each country there are 20 varibles with each variable representing a different qualitative or quantitative feature of that country.

Comparative boxplot for the average GDP per capita of each region: 
![](/gdp.png)

Hexplot to display the strong relationship between the GDP per capita and the number of phones of each country:
![](/phones.png)

#### Conclusion 
4 different learning regressors (Linear Regression, SVM, Random Forest, and Gradient Boosting) were tested and we have achieved the best prediction performance using Random Forest, followed by Gradient Boosting, then Linear Regression, while SVM achieved the worst performance of the four.

Best results from the four differnet models:
![](/overall_performance.png)

The best prediction performance was achieved with a Random Forest regressor, using all of the features in the dataset which resulted in the following metrics:

* Mean Absolute Error (MAE): 2142.13
* Root mean squared error (RMSE): 3097.19
* R-squared Score (R2_Score): 0.8839

(gdp_per_capita values in the dataset ranges from 500 to 55100 USD).

Random Forest Regressor:
![](/Prediction_performance.png)

