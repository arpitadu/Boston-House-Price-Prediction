# Boston-House-Price-Prediction
'Boston house price prediction' project is designed to forecast the median values of houses in Boston by taking into account multiple factors, including the area's crime rate, the ages of the homeowners, the number of businesses, and much more.

**Background:**

Boston, Massachusetts, is a dynamic metropolitan area characterized by its diverse population, socioeconomic diversity, environmental factors, and varied housing structures—all of which significantly influence housing prices. Understanding these factors and predicting housing price trends is crucial for real estate companies, policymakers, investors and homebuyers alike. The housing market in this dynamic region is complex and often time-consuming to navigate, shaped by a multitude of variables that impact market dynamics and investment strategies. 

In this current data era, house prices can be predicted accurately by leveraging data-driven analytical and machine-learning approaches. Therefore, this project aimed to estimate the median prices of owner-occupied homes in Boston by taking into account influencing socio-economic and environmental factors.

**Analysis**

Boston house price prediction was conducted using machine learning techniques. Initially, data variance and correlation analyses were employed to reduce non-important and redundant variables. Outliers were treated using the Winsorizing method. Subsequently, the data was split into training and testing sets in an 80-20 ratio, and both sets were scaled. Following this, four different regression models—linear regression, random forest, support vector machine, and gradient boosting—were trained. Hyperparameters were tuned using grid search with cross-validation. The performances of these models on the test set are summarized below.
| Regression Model              | Mean Squared Error | R-squared | Maximum Error |
|-------------------------------|--------------------|-----------|---------------|
| Linear Regression             | 31.52              | 0.57      | 19.2          |
| Random Forest Regressor       | 17.64              | 0.76      | 24.63         |
| Support Vector Regressor      | 31.64              | 0.57      | 32.4          |
| Gradient Boosting Regressor   | 17.00              | 0.77      | 25.17         |


**Findings**

The Gradient Boosting Regression model with ten input variables can predict the median house prices in Boston with a mean squared error of 17.0 and 77% accuracy.  Developed a regression model that can predict Boston house prices. Socioeconomic variables such as the lower status of the population (LSTAT) and the average number of rooms per dwelling (RM) were the most significant predictors. The house prices increased as the lower-status population decreased in a neighbourhood. In contrast, larger homes with more rooms tended to have higher prices, reflecting a preference for more spacious living conditions. Following these two factors, proximity to employment centres and the crime rate per capita played significant roles in determining house prices. These findings can guide real estate professionals, policymakers, and investors in understanding the key determinants of housing prices and making informed decisions. 

