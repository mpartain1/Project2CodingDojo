# Red Wine Analysis
## The purpose of this project is to create a production-quality model that predicts the quality of red wine from a variety of different factors.  The data was taken from the UCI machine learning repository and contains attributes such as fixed acidity, chlorides, and residual sugar in the determination of wine quality, rated on a scale from 0 to 10.

# Methods
## Explored data through boxplots for each variable in order to understand the existence of outliers and overall distribution.  Created a correlation plot to understand the correlations of each variable, finding that the most influential variable in determining wine quality was alcohol (unsurprisingly).  Created a tuned decision tree regression model and a tuned bagged regression model, analyzing the regression metrics for each.  Also implemented Principal Component Analysis on the Bagged Regression model to explore the effect on its metrics.  

# Conclusion
## Overall, the tuned bagged regression model without PCA had the lowest MAE and MSE on the training and testing data.  As a result, this is the most accurate regression model for production purposes.  This model can be applied to stakeholders who are in charge of either investing in wineries responsbile for producing certain types of wines or for the practical application of wineries themselves looking to formulate the most profitable type of red wine.
