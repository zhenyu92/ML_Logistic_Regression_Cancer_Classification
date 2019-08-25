# A study on Cancer Classification using Logistic Regression.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
You have been hired as a data scientist provide a model, which is able to predict if the cancer diagnosis is benign or malignant based on several observations / features.

`Predictors:`
```
Radius (mean of distances from center to points on the perimeter)
Texture (standard deviation of gray-scale values)
Perimeter
Area
Smoothness (local variation in radius lengths)
Compactness (perimeter^2 / area - 1.0)
Concavity (severity of concave portions of the contour)
Concave points (number of concave portions of the contour)
Symmetry 
Fractal dimension ("coastline approximation" - 1)
```

`Target:`
```
Result(1: Benign, 0: Malignant)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Logistic_Regression_Cancer_Classification/blob/master/SVM%20-%20Cancer%20Classification.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Exploring the Variables
      3.2 Visualizing the Variables
    4 Train Test Split
    5 Select and Train a Model
      5.1 Support Vector Machine Model
    6 Apply Model on Test Set
      6.1: Improving the Model
      6.2 Applying GridSearch
    ```
    
### Model Performance
The model has an average `Precision` & `Recall` of 97%.
![alt text](https://github.com/zhenyu92/ML_Logistic_Regression_Cancer_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
