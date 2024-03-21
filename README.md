# K-Nearest Neighbors (KNN) Algorithm for Diabetes Prediction

## Description:
The K-Nearest Neighbors (KNN) algorithm is utilized in this Python implementation to predict diabetes based on various medical features. The algorithm utilizes the scikit-learn library for machine learning tasks.

## Summary:
1. **Importing Libraries:** The necessary libraries such as numpy, pandas, scikit-learn, and math are imported for data manipulation, machine learning model creation, and evaluation.

2. **Loading and Preprocessing the Dataset:** The dataset containing medical data is loaded, and zero values in certain columns like "Glucose", "BloodPressure", "SkinThickness", "Insulin", and "BMI" are handled by replacing them with the mean of non-zero values. The dataset is then split into training and testing sets.

3. **Feature Scaling:** Standard scaling is applied to the features to standardize their range, ensuring that they contribute equally to the model's performance.

4. **Training the KNN Model:** The optimal value of 'k' (number of nearest neighbors) is determined using the square root of the number of samples in the test set. The KNN model is trained using the training data.

5. **Making Predictions:** The trained model is used to predict the outcomes (diabetes or non-diabetes) for the test dataset.

6. **Evaluating Model Performance:** The confusion matrix is calculated to assess the model's performance. Total accuracy, class-specific accuracies, and geometric mean accuracy are computed and printed to evaluate the effectiveness of the model in predicting diabetes.

## Dataset:
The dataset used in this implementation can be found [here](/kaggle/input/ml-labexercice05/KNN_Dataset (1).csv).

## Additional Notes:
- Ensure all required libraries are installed before running the code.
- The dataset should be placed in the appropriate directory or path specified in the code.
- Adjustments to parameters such as test size, random state, and metric can be made according to specific requirements.
