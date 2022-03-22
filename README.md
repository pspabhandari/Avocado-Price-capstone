# Avocado-Price-capstone
I was looking for the avocado total sale price and how other features affects its selling power, if they are positively or negatively correlated to total price of avocado sale and come up with a better model for prediction.
From visualization I found that most of the production of Avocado happens in California.
After data processing, data cleaning, exploration to see any outliers, correlation between features to avoid multicollinearity, and PCA to reduce multicollinearity, I came up with some features that might be highly correlated to total price of avocado but not with other features to get better prediction.
Next, I split data into training and testing data sets, I trained model by implementing some changes in the features to get better model and predicted the model.
To get better prediction I tried several regression models like Linear regression/knn/decision tree/random forest/SVR/gradient boosting and hyper tuning with regularization ridge/lasso/elastic net to get better model.
Among them I found KNN as a better model which gave higher accuracy, better prediction, and lower error than other models.
