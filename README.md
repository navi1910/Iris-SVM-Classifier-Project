# SVM - Iris - Classifier Project

Project for classifying the 'species' - Target Labels of Iris dataset using SVM Classifier.

<img src='http://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg' height=300 width=300>

<img src='http://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg' height=300 width=300>

<img src='http://upload.wikimedia.org/wikipedia/commons/9/9f/Iris_virginica.jpg' height=300 width=300>

#### To classify the oberservations into the right Target Labels.
The iris dataset contains measurements for 150 iris flowers from three different species.

The three classes in the Iris dataset:
* Iris-setosa (n=50)
* Iris-versicolor (n=50)
* Iris-virginica (n=50)

#### The four features of the Iris dataset:
* sepal length in cm
* sepal width in cm
* petal length in cm
* petal width in cm

## Methods
* Machine Learning - Support Vector Machines
* Supervised Learning - Classification
* Data Visualization
* Exploratory Data Analysis

## Technologies used
* Jupyter Notebook
* Python
    * Pandas
    * Numpy
    * Warnings
    * Scikit-Learn
    * Matplotlib
    * Seaborn

<img src='https://github.com/navi1910/Iris-SVM-Classifier-Project/blob/main/kdeplot.png'  height=50% width=50%>

## Procedure
* Import the required python modules.
* Load the data as a Data-Frame using seaborn module.
*Note: Iris data is built-in in Seaborn python module.*
* Check the basic information about the data.
* Perform exploratory data analysis using data visualization.

<img src='https://github.com/navi1910/Iris-SVM-Classifier-Project/blob/main/pairplot.png' height=50% width=50%>

## Model Building
* Separate the Dependent and Independent variables.
* Split the data into Train and Test datasets.
* Initialize SVC (Support Vector Classifier) and assign variable.
* Fit the training data and predict the target labels for test dataset.
* Evaluate using the appropriate metrics.

## GridSearchCV
* Create dictionary with the required parametersto be tuned.
* Assign variable to GridSearchCV along with the parameters.
* Fit training data to GridSearchCV.
* Get best_score_, best_params_, and best_estimator.
* Predict the target labels for test dataset using GridSearchCV.
* Evaluate the model to get the results..

## Results:

<img src='https://github.com/navi1910/Iris-SVM-Classifier-Project/blob/main/Results.png' height=50% width=50%>
