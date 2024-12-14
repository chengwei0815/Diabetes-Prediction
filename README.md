# Diabetes Prediction using Support Vector Machine (SVM)

This project involves building a machine learning model to predict whether a person has diabetes or not. We will use the **Support Vector Machine (SVM)** algorithm to classify the data and predict diabetes based on various medical parameters. The dataset used in this project is the PIMA Indian Diabetes Dataset, which contains information about female patients and their medical data such as blood glucose levels, insulin levels, body mass index (BMI), etc.

## Project Workflow

### 1. **Problem Understanding**
   - The goal of the project is to predict if a person has diabetes or not based on medical information. The target variable (label) is binary, where:
     - `1`: The patient is diabetic.
     - `0`: The patient is non-diabetic.

### 2. **Support Vector Machine (SVM) Algorithm**
   - SVM is a supervised machine learning algorithm used for classification. It works by finding the best hyperplane that separates data points from different classes.
   - In this case, the SVM model will use medical data such as blood glucose, insulin levels, BMI, and other parameters to classify the data as either diabetic or non-diabetic.

### 3. **Data Preprocessing**
   - We will perform data preprocessing to ensure the data is clean, standardized, and ready to be fed into the machine learning model.
   - This includes handling missing values, normalizing numerical data, and splitting the data into training and testing datasets.

### 4. **Model Training and Evaluation**
   - The data will be split into training and testing sets.
   - We will train the SVM model using the training data and evaluate its performance on the test data.
   - The performance will be assessed using metrics like accuracy.

### 5. **Prediction**
   - Once the model is trained, it will be used to predict whether a new patient is diabetic or non-diabetic based on their medical data.

![Diabetes Prediction Image](diabetes.png)


## Prerequisites

Before running the code, make sure you have the following libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib` (optional for visualizations)

You can install these dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib

