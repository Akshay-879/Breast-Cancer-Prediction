# Breast-Cancer-Prediction

## Description

Project Description:
This project aims to analyze breast cancer data using the K-nearest neighbors (KNN) algorithm. The project is divided into several steps.

In the first step, the breast cancer dataset is loaded and preprocessed. The dataset consists of various features such as radius, texture, perimeter, area, smoothness, compactness, concavity, points, symmetry, and dimension. The dataset also includes the diagnosis (M for malignant and B for benign) as the target variable. The unnecessary "id" column is dropped from the dataset.

The next step involves splitting the dataset into training and testing sets using the train_test_split function from the sklearn library. The training set will be used to train the KNN classifier, while the testing set will be used to evaluate the performance of the classifier.

After splitting the dataset, the KNN classifier is created with the KNeighborsClassifier class from the sklearn library. In this project, the classifier is set to use 5 neighbors and the weights are set to 'distance', meaning closer neighbors will have a higher influence on the classification.

Once the classifier is created, it is trained on the training data using the fit method. The fit method calculates the distances between the data points and stores them internally for future predictions.

After the classifier is trained, it is evaluated on the testing data using the score method. The score method calculates the accuracy of the classifier by comparing the predicted labels with the actual labels.

Finally, the project includes an analysis of the class distribution among benign (B) and malignant (M) diagnoses. The dataset consists of approximately two-thirds benign cases and one-third malignant cases. This distribution is taken into consideration to ensure the model performs well for both classes.

### Programing Language: 
1. Python

### Libraries:
1. Numpy
2. Pandas
3. Plotly
4. Seaborn
5. Sklearn
