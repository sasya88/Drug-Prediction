# Drug Classification Model

## overview
The primary objective of this analysis is to develop a predictive model that can determine the most appropriate drug for a future patient suffering from a specific illness. Each patient in the dataset has been treated with one of five medications: Drug A, Drug B, Drug C, Drug X, or Drug Y. By analyzing the relationships between the patients' features—such as age, sex, blood pressure,Na_to_K and cholesterol levels—and their respective drug responses, we aim to build a model that can accurately recommend the best medication for new patients based on their individual characteristics. This predictive capability is crucial for optimizing treatment strategies and improving patient outcomes.

## Table of Contents
- [Libraries Used]
- [Dataset](#dataset)
- [Modeling Process]
- [Results]

## Libraries Used
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn (for data visualization)

## Dataset
The dataset used in this project includes patient information such as:
- Age
- Sex
- Blood Pressure
- Cholesterol
- Drug response (target variable)

The data was preprocessed to handle missing values, encode categorical variables, and normalize features.

## Modeling Process
1. **Data Exploration**: Analyzed the dataset to understand distributions and relationships between features.
2. **Preprocessing**: 
   - Handled missing values
   - Encoded categorical variables
   - Normalized numerical features
3. **Model Selection**: 
   - Split the dataset into training and testing sets
   - Experimented with various algorithms including Logistic Regression, Decision Trees, Random Forests and Stacking Classifier.
4. **Model Evaluation**: 
   - Evaluated model performance using accuracy, precision, recall, and F1 score.
   - Used confusion matrices to visualize results.

## Results
- The Random Forest model achieved the highest accuracy of 98% on the test dataset.
- Confusion matrix and classification report indicate the model's effectiveness in predicting drug responses.
