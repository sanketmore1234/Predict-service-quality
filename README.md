# Predict-service-quality
1. To predict Service Quality as Good or Bad (binary classification) from Hospital data
2. To guage the parameters important to the service quality levels (Finding influencial features)

# Adult-Census-Income-Prediction
Adult Census Income Prediction Machine Learning project

# Libraries Used
1. Pandas
2. Scikit Learn
3. Matplotlib
4. Numpy

# Algorithms Used
1. Logistic Regression
2. Ridge Classifier
3. Random Forest Classifier

# Data cleaning
There are no null values in the dataset, hence we are good to go ahead with the modeling

# Data Transformation
Standard Scaling the parameters (Quantitative)

# Hyper Parameter Tuning
Used gridsearch CV for hyper parameter tuning

# Cross Validation
k fold cross validation, used scoring parameter as f1 (since the false positives were more important) and also looking at class wise f1 scores

# Performance Criteria
Selected the best performing model keeping in mind F1 and Recall scores

# Finding influential features
The model coefficients of features were used to guage the most important parameters which influenced the service quality. The same are shown in a graphical manner in the python notebook
