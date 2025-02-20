# ZCH-Sound-Open-Source-ZJU-Pediatric-Heart-Sound-Database-with-Congenitial-Heart-Disease (Heart Disease Prediction)

## Overview
This project uses machine learning techniques to predict heart disease based on a given dataset (`heart.csv`). The dataset is preprocessed, and multiple classification models are applied to determine their effectiveness.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Models: Logistic Regression, Naïve Bayes, KNN, SVM, Decision Tree, Random Forest

## Project Structure
- **Data Loading**: Reads heart disease data from `heart.csv`
- **Preprocessing**: Handles categorical data and prepares it for model training
- **Model Training & Evaluation**:
  - Splits data into training and testing sets
  - Applies multiple classification models
  - Evaluates performance using confusion matrix, accuracy, and classification report

## Installation
1. Install dependencies using:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Run the Jupyter Notebook (`Heart_Disease_Prediction.ipynb`) to execute the analysis.

## Usage
- Modify `heart.csv` to include new data for predictions.
- Experiment with different models and hyperparameters to improve accuracy.

## Results
The notebook includes model evaluation metrics to compare performance and identify the best classifier for heart disease prediction.
