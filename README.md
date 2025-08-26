# diabetes_prediction-project
Analyze and predict diabetes outcomes using the Pima Indians Diabetes dataset. This notebook covers data exploration, visualization, data cleaning, and applies KNN, Decision Tree, MLP, and Random Forest models to classify diabetes, including model evaluation.

# Diabetes Prediction Project

This project analyzes and predicts diabetes outcomes using the Pima Indians Diabetes Dataset. It includes data preprocessing, exploratory data analysis, visualization, and machine learning model implementation.

## Project Structure

```
.
├── diabetes_prediction.ipynb   # Main Jupyter notebook for analysis and modeling
├── diabetes.csv                # Dataset used for prediction
```

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

Install dependencies using:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

## Usage

1. Clone or download this repository.
2. Open `diabetes_prediction.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells sequentially to:
   - Load and preprocess the data
   - Perform exploratory data analysis and visualization
   - Train and evaluate machine learning models (KNN, Decision Tree, MLP, Random Forest)

## Data

The dataset [`diabetes.csv`](diabetes.csv) contains the following columns:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (target variable: 0 = No diabetes, 1 = Diabetes)

## Features

- Data cleaning and preprocessing (handling zeros as missing values)
- Exploratory data analysis and visualization
- Model training and evaluation with multiple classifiers
- Accuracy comparison for different models

## Results

The notebook displays accuracy scores for each model and visualizes the results to help select the best-performing classifier.

## License

This project is for educational
