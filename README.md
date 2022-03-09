# House-Price-Prediction-Kaggle--Predictive-Modelling

House Price Prediction (Kaggle) -Predictive Modelling

•	Libraries – SKlearn, Pandas, Seaborn and NumPy.
•	Dataset -  Ames Housing dataset  (Kaggle Competition)
•	Model    – Regression 

            The competition is to create and ML model to predict the price of a given house. As a part 
of Machine Learning competition participants will be provided a training data set with house details as feature and house price as target and test data(without price) to predict the target values. 

1.Exploratory Data Analysis has done using Pandas & Seaborn, based on the analysis dropped few features which are highly correlated with other features. Feature to drop selected based on the amount of Nan in it.

2.Pre-processing: Applied Information gained through EDA and the input documents used to fill the missing values (NaN) as well as new feature extraction (e.g.: bin the continuous values to create new featured class).


Used Yeo-Johnson to transform the skewed features. Normal Imputation methods with Mean, Mode and the information from the input document used the handle the NaN. Applied label encode to categorical Text data converted into numerical class data.
3.Base Line Model: After tried few models, final base model created with  Ridge, Lasso, Gradient Boosting and ElasticNet since it gives better score in stratified k-Fold CV.

4.Hyper Parameter Optimization: Hyperparameter optimization, done using Grid search.

5.Ensemble model: Custom ensemble model created by calculating the mean of all the four models’ prediction.
