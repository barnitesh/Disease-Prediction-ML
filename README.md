# Disease-Prediction-ML
# Disease_Prediction_ML
This project is a disease prediction system that takes symptoms as input and predicts the most likely disease using three machine learning models: Support Vector Machine (SVM), Gaussian Naive Bayes (GaussianNB), and Random Forest. The final prediction is determined by taking the mode of the predictions from these models. 
# Disease Prediction System

## Description

Hii!! My name is NITESH BARMAN
This project is a disease prediction system that uses machine learning models to predict the most likely disease based on input symptoms. The system leverages three different models: Support Vector Machine (SVM), Gaussian Naive Bayes (GaussianNB), and Random Forest. The final prediction is determined by taking the mode of the predictions from these models. The system is designed to handle missing data and provides visual insights through confusion matrices.

## Features

- **Input Symptoms**: Users can input symptoms separated by commas.
- **Multiple Models**: Utilizes SVM, GaussianNB, and Random Forest models.
- **Final Prediction**: Combines predictions using the mode to provide a final diagnosis.
- **Confusion Matrix**: Visualizes the performance of the models on the test data.
- **Data Handling**: Can manage missing data effectively.

## Python Libraries Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **scikit-learn**: For machine learning models and utilities.
- **matplotlib**: For plotting and visualization.
- **seaborn**: For statistical data visualization.
- **collections**: For handling collections and counters.
- **warnings**: For managing warnings and ignoring unnecessary ones.

## Technologies Used

- **Machine Learning**: SVM, Gaussian Naive Bayes, Random Forest.
- **Data Visualization**: Confusion matrices using matplotlib and seaborn.
- **Data Processing**: Handling and cleaning data with pandas and numpy.

## Project Workflow

1. **Data Preparation**:
   - The dataset is loaded, and features and target variables are extracted.
   - Data is split into training and test sets.
   - Missing values are handled appropriately.

2. **Model Training**:
   - Three different models (SVM, GaussianNB, and Random Forest) are trained using cross-validation.
   - The models are then trained on the entire dataset to create final models.

3. **Symptom Index Creation**:
   - A dictionary mapping symptoms to their respective indices is created.
   - This allows easy conversion of input symptoms to the required format for model prediction.

4. **Disease Prediction**:
   - Users input symptoms separated by commas.
   - The system processes these symptoms and makes predictions using the trained models.
   - The final prediction is determined by taking the mode of the predictions from the three models.

5. **Model Evaluation**:
   - The accuracy of each model is evaluated on the test set.
   - Confusion matrices are generated to visualize the performance of the models.

## Accuracy

- The project includes accuracy evaluation for each model on both the training and test sets.
- Accuracy scores are provided for each model, and overall accuracy is determined by combining the model predictions.
- Confusion matrices are used to visualize and understand the model performance better.


    - The script will prompt you to enter symptoms separated by commas.
    - The system will then output the predicted disease along with individual predictions from each model.

