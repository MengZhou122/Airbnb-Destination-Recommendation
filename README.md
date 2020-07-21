# Final project for INFO6105(Data Science Engineering Methods)

Data source: Kaggle, https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data

Training data1 offered by Airbnb contains 62 thousand users’ information: age, gender, registered device, browser, sign-up method, data of first booking, country destination, etc.

Training data2 contains 10 millions of their operations and time periods of the operations before first booking.

Based on this data, we will build a model to predict the country of destination of a new registered user based on his/her information and operations.

Preprocessed and purified raw data with Python on Jupyter Notebook with Pandas, Scikit-learn, Numpy libraries

Applied multiple classifiers (KNN, Naive Bayes, Random Forest, XGBoost), various hyperparameter combinations and Cross-validation to select the most proper model, presented the result in graphs with matplotlib

Optimized final model and got 0.70 NDCG and 65% accuracy, ranked top 15% among all competition participants
