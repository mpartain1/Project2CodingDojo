# Red Wine Analysis
The purpose of this project is to create a production-quality model that predicts the quality of red wine from a variety of different factors.  The data was taken from the UCI machine learning repository and contains attributes such as fixed acidity, chlorides, and residual sugar in the determination of wine quality, rated on a scale from 0 to 10.

# Methods
I explored data through boxplots for each variable in order to understand the existence of outliers and overall distribution.  I created a correlation plot to understand the correlations of each variable, finding that the most influential variable in determining wine quality was alcohol (unsurprisingly).  I created a tuned decision tree regression model and a tuned bagged regression model, analyzing the regression metrics for each.  I also implemented Principal Component Analysis on the Bagged Regression model to explore the effect on its metrics.  

# Data Analysis
![image](https://user-images.githubusercontent.com/105669219/183987508-b6fb4caa-402f-4ecd-a112-329f2ac0c366.png)

From here we can see that generally speaking, higher alcohol levels correspond to higher quality ratings.  Using this information, perhaps a stakeholder would decide to invest more resources into the fermentation process of wine in order to produce higher alcoholic levels and therefor a higher quality wine to be sold.

![image](https://user-images.githubusercontent.com/105669219/183987563-4b512299-6b8a-48a8-acb8-c8da0367ed93.png)

From this graph, we can see that there is a strong positive correlation between fixed acidity levels and the density of the wine.  In terms of practical application, if a stakeholder wanted to decrease a wine's density for various reasons, they could begin by taking a look at how to reduce fixed acidity levels due to this correlation.

# Conclusion
Overall, the tuned bagged regression model without PCA had the lowest MAE and MSE on the training and testing data.  As a result, this is the most accurate regression model for production purposes.  This model can be applied to stakeholders who are in charge of either investing in wineries responsbile for producing certain types of wines or for the practical application of wineries themselves looking to formulate the most profitable type of red wine.
