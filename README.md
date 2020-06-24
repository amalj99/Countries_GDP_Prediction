# Countries_GDP_Prediction

## Objective
Our objective is to:
* Understand the data and get valuable insights from it.
* Use various Supervised Learning techniques to create a Machine Learning model capable of accurately predicting the GDP per capita of a country based on various dependent features(population, literacy, birthrate, climate ,etc).

## Code and Resources used
* Python Version: 3.7
* Packages used: Pandas, Numpy, Matplotlib, Seaborn and Plotly
* Data: https://www.kaggle.com/fernandol/countries-of-the-world

## Data Description
The dataset contains 227 rows and 20 columns, where each row corresponds to a unique country and each column measures a characteristic of that country that contributes to its GDP.

## Observations
* From the plot below we find that the countries with the highest GDP per capita are present mainly in Western Europe and North America.
![](https://github.com/amalj99/Countries_GDP_Prediction/blob/master/Images/Country%20GDP.png)

* This plot displays the predictions of our optimized Gradient Boosting model. The red dots represent the predictions and the blue line corresponds to the line that would be formed by ideal predictions.
![](https://github.com/amalj99/Countries_GDP_Prediction/blob/master/Images/GBM%20Pred%20Plot.png)

* Here we see the importance of each feature in the optimized Gradient Boosting model. The importances assigned by the model are fairly distributed and we do not see any, single feature with extremely high importance.
![](https://github.com/amalj99/Countries_GDP_Prediction/blob/master/Images/GBM%20Feature%20Importance.png)

## Conclusion
3 different learning regressors (Linear Regression, Random Forest, and Gradient Boosting) were tested. We acheived the best prediction performance using Gradient Boosting Regressor , followed by Random Forest Regressor, while Linear Regression achieved the worst performance of the 3. 

The best prediction performance was acheived using ***Gradient Boosting Regressor*** , using all features in the dataset, and resulted in the following metrics:

* Root Mean Squared Error(RMSE): ***2447.968934551082*** 
* Mean Absolute Error(MAE): ***1865.1781159964487*** 
* R-Squared Score(R2 Score): ***0.9277099481978738*** 
