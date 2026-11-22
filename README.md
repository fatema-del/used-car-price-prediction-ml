# used-car-price-prediction-ml
A machine learning project that uses Linear Regression and Decision Tree Classification to analyze used car data and predict car prices and price categories.
# Used Car Price Prediction and Classification

## Project Overview
This project uses machine learning to analyze used car data. Our goal is to predict used car prices and classify cars into different price categories based on their features.

## Project Objectives
- Predict used car prices using Linear Regression.
- Classify used cars into Low, Medium, and High price categories using Decision Tree Classification.
- Evaluate the performance of both models using different evaluation metrics.
- Use cross-validation and Grid Search to test and improve model performance.

## Dataset
We used a cleaned used car dataset containing information about vehicles, such as year, manufacturer, model, condition, fuel type, transmission, odometer, car age, and other features.

## Machine Learning Models

### Linear Regression
Linear Regression was used to predict the numerical price of used cars. The model was evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R².

### Decision Tree Classifier
A Decision Tree Classifier was used to classify cars into three price categories:

- **Low:** Below $7,500
- **Medium:** $7,500 to less than $16,800
- **High:** $16,800 or above

The classifier was evaluated using Accuracy, Precision, Recall, and F1-score.

## Model Tuning

Grid Search with cross-validation was used to test different model parameters and select the best settings.

### Linear Regression
- Best parameter: `fit_intercept=False`
- Best CV MAE: `5771.38`

### Decision Tree
- Criterion: `gini`
- Maximum depth: `10`
- Minimum samples per leaf: `5`
- Best CV Accuracy: `0.7125`

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Project Files
- **Google Colab Notebook (.ipynb):** Includes our code, data preparation, model building, evaluation, and tuning.
- **Cleaned Dataset (.csv):** The dataset used for our machine learning models.
- **Project Report (.docx):** Contains the project explanation, methodology, model results, evaluation, screenshots, and conclusions.

## Conclusion
In this project, we used Linear Regression and Decision Tree Classification to analyze used car data. We evaluated both models and used Grid Search to test their parameters. The project helped us understand how machine learning can be used for price prediction and classification.

## Team Project
This project was completed as part of our machine learning course.
