# Diabetes Prediction using Support Vector Machine (SVM)

## Project Overview

This project develops a Machine Learning-based Diabetes Prediction System using the Support Vector Machine (SVM) algorithm.

The system analyzes patient health-related information and predicts whether a person is likely to have diabetes or not.

The project uses data preprocessing, feature scaling, model training, and evaluation techniques to build a diabetes classification model.

## Dataset

The project uses the **Pima Indians Diabetes Dataset**.

- Dataset: Pima Indians Diabetes Dataset
- Input Features: Patient health-related measurements
- Target Variable: Diabetes Outcome
- 0: Non-Diabetic
- 1: Diabetic

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Support Vector Machine (SVM)
- StandardScaler
- Jupyter Notebook
- Google Colab

## Project Workflow

1. Dataset Loading
2. Data Exploration and Analysis
3. Data Preprocessing
4. Handling Missing or Invalid Values
5. Feature Selection
6. Feature Scaling using StandardScaler
7. Train-Test Splitting
8. SVM Model Training
9. Diabetes Prediction
10. Model Evaluation
11. Confusion Matrix Visualization
12. Model Saving

## Machine Learning Algorithm

**Support Vector Machine (SVM)**

SVM is a supervised Machine Learning algorithm used for classification tasks. It identifies an optimal decision boundary to distinguish between diabetic and non-diabetic cases.

## Model Evaluation

The model performance is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Project Files

- `Diabetes_Prediction_SVM.ipynb` – Complete Jupyter Notebook
- `pima_indians_diabetes.csv` – Dataset used for training and testing
- `diabetes_svm_model.pkl` – Trained SVM model
- `confusion_matrix.png` – Model evaluation visualization
- `requirements.txt` – Required Python libraries
- `README.md` – Project documentation

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Open the Jupyter Notebook.
4. Run the notebook cells in sequence.
5. Provide patient health-related input data to perform diabetes prediction.

## Future Improvements

- Improve prediction performance through hyperparameter tuning.
- Compare SVM with other Machine Learning algorithms.
- Develop a user-friendly web application using Streamlit.
- Add more visualizations for better understanding of predictions.

## Disclaimer

This project is developed for educational purposes only. It is not intended to replace professional medical diagnosis or advice.# Diabetes-Prediction-SVM
Machine Learning project for diabetes prediction using Support Vector Machine (SVM) and Python.
