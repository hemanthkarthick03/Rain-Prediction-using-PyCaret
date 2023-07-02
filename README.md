# Rain-Prediction
A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset
This project is tested over lot of ml models like catboost, xgboost, random forest, support vector classifier, etc..
Out of these models catboost performed very well giving an AUC score around and ROC score of 89 far better than others.
Here due to my system compatibility is very low. So I havent done hyperparameter tuning. But it is highly recommended to do it if possible.
# Website Link: ["https://rainy-brain.herokuapp.com/"](https://rainy-brain.herokuapp.com/)

# Tech Stack
* Front-End: HTML, CSS, Bootstrap
* Back-End: Flask
* IDE: Jupyter notebook, Pycharm

# Data Collection: 
[Rainfall Prediction in Australia dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) from Kaggle

# Data Preprocessing: 
* Missing Values Handled by Random Sample imputation to maintain the variance
* Categorical Values like location, wind direction are handled by using Target guided encoding
* Outliers are handled using IQR and boxplot
* Feature Selection and was done but didnt perform well it can be seen in testing_notebook/Prediction.ipynb
* Feature Scaling didnt give a lot of difference it also can be seen in testing_notebook/RainPrediction1.ipynb
* Imbalanced Dataset was handled using SMOTE


![image](https://github.com/phoenix-mp3/Rain-Prediction-using-PyCaret-and-ML-model/assets/128579996/5f40ca58-a3a0-4ddf-ba31-0439932bfdbe)


# Model Creation:
* Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.
* Out of these catboost, random forest and support vector machines were top 3
* The conclusion were made using classification metrics. roc curve and auc score

![image](https://github.com/phoenix-mp3/Rain-Prediction-using-PyCaret-and-ML-model/assets/128579996/f6f6bd64-c503-4cab-86a9-dd8ad5eb7dbb)


# Model Deployment
* The model is deployed using Flask at Heroku server at the [link](https://rainy-brain.herokuapp.com/)

# If you like this project please do give a star. I am also giving my LinkedIn profile. If you want we can connect there too
