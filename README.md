# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*Company*:CODETECH IT SOLUTIONS

*Name*:SAI VEEKSHANA THOTA

*Intern ID*:CT6WRAK

*Domain*:PYTHON PROGRAMMING

*Duration*:6 WEEKS

*Mentor*:NEELA SANTOSH

This code implements a machine learning model using the Random Forest algorithm to classify iris flower species based on the well-known Iris dataset. The dataset is loaded using `sklearn.datasets.load_iris()` and converted into a Pandas DataFrame. The features (sepal length, sepal width, petal length, and petal width) are separated from the target variable, which represents the species classification. The data is then split into training and testing sets using an 80-20 ratio with stratified sampling. Feature scaling is applied using `StandardScaler` to normalize the dataset, ensuring better model performance. 

A `RandomForestClassifier` with 100 estimators is trained on the preprocessed data, and predictions are made on the test set. The model's performance is evaluated using accuracy, a classification report, and a confusion matrix. The accuracy score is printed, along with a detailed classification report that includes precision, recall, and F1-score for each class. The confusion matrix is visualized using Seaborn's heatmap to illustrate model predictions against actual labels. The result is a well-structured ML pipeline that demonstrates data preprocessing, model training, evaluation, and visualization.


OUTPUT:
![image](https://github.com/user-attachments/assets/e31f116d-1e12-45b0-9500-3195478a4304)





