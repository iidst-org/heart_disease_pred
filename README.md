# Heart Disease Prediction

## Overview
The **Heart Disease Prediction** project aims to analyze medical data and build a predictive model to determine the likelihood of heart disease in individuals. Using machine learning techniques, the model evaluates key health indicators and provides a risk assessment.

## Dataset
The dataset used in this project is **heart.csv**, which contains various health-related attributes, such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- Oldpeak (ST depression induced by exercise)
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia type
- Target (0 = No disease, 1 = Disease present)

## Dependencies
To run this project, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Model Development
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**
   - Visualizing feature distributions
   - Correlation analysis
3. **Model Training**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC Curve analysis

## Usage
Run the Jupyter Notebook **Heart Disease Prediction.ipynb** to execute the analysis and model training. Modify parameters as needed to optimize performance.

## Results
The model provides predictions on the likelihood of heart disease based on patient data. The evaluation metrics help determine the best-performing algorithm.

## Contributions
Feel free to contribute by improving the model, refining the dataset, or enhancing visualization techniques.
