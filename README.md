# IRIS-Flower-Classification-Mini-Project

The main objective of this mini-project is to learn more about classification problems and the algorithm Support Vector Machine also known as the Support Vector Network. 

Steps in this Project: 

  ```
  1. Load and visualise our Dataset
    1.1 -> using .describe() & Seaborn(sns)
    1.2 -> Create our columns (Sepal & Petal Width/Height)

  2. Analyse & Visualise Dataset
    2.1 -> Using sns.pairplot
    2.2 -> Plot the average of each feature (reshape our array to (4(features), 3(classes)) array)
      2.2.1 -> List comprehension to get the average

  3. Model Training
    3.1 -> Import SVC (Support Vector Classifier) from scikit-learn SVM
    3.2 -> Create svn Object
    3.3 -> Feed training dataset into algorithm by using svn.fit() method

  4. Model Evaluation
    4.1 -> Predict from test dataset "svn.predict(X_test)"
    4.2 -> import accuracy score from sklearn.metrics
    4.3 -> Detailed classification report
      4.3.1 -> precision, recall, f1-score & support

  5. Testing Model
    5.1 -> Create a new, random made dataset of values
    5.2 -> Predict the species from output vectors
    5.3 -> Save model using pickle   
  ```
