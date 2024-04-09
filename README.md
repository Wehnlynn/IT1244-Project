# IT1244 Project
 
How to run the project:
1. Download data.csv from the data folder
2. Run EDA.ipynb to do Exploratory Data Analysis on data.csv to see which features are more important.
3. Run bootstrap_find_outliers.ipynb to find indices of outliers, change the labels of the outliers, and split the modified data into training and testing datasets.
4. Save X_train_stand.npy, X_test_stand.npy, y_train.npy, y_test.npy.
5. Run each of the model python notebook(KMeans.ipynb, ANN.ipynb, Logistic Regression.ipynb, Decision Tree.ipynb) to train each of the models with our dataset that is saved in step 4 to find the predictions and find the accuracy of the model. 
