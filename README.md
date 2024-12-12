# NutriRate - Machine Learning Model

## Overview
NutriRate is a machine learning model designed to evaluate and rate food items based on their nutritional content, helping users make informed dietary choices. The model assigns a health grade from **A (Healthy)** to **E (Avoid)** based on user-provided nutritional data. It uses supervised learning to predict the rating and provide insights about a food's suitability for regular consumption.

## Problem Statement
Nutritional labels can be difficult to interpret, leading consumers to make unhealthy choices. NutriRate simplifies this process by offering an easy-to-understand grading system, helping combat health issues like obesity and diabetes.

---

## Objective
The main goal of this machine learning model is to:
- Predict food grades (A to E) based on key nutritional values.
- Provide users with actionable insights about food healthiness.

---

## Features and Workflow
1. **User Input:** Users enter nutritional information like calories, fat, sugar, protein, sodium, etc.
2. **Preprocessing:** The data undergoes cleaning and transformation.
3. **Model Prediction:** A trained supervised learning model predicts a grade (A to E).
4. **Feedback:** The model outputs the grade along with a brief interpretation:
   - **A** - Highly healthy food
   - **B** - Healthy, consume regularly
   - **C** - Neutral, moderate intake recommended
   - **D** - Unhealthy, limit intake
   - **E** - Avoid consuming

---

## Model Architecture
The NutriRate machine learning model uses:
- **Algorithm**: Supervised classification (Neural Network).
- **Framework**: TensorFlow.
- **Data Input**: Cleaned nutrition dataset containing macronutrient values.
- **Labels**: Graded classification labels (A, B, C, D, E).

### Workflow:
1. **Data Collection**: Nutritional datasets are prepared and preprocessed.
2. **Feature Engineering**: Nutritional content (e.g., sugar, calories) normalized and scaled.
3. **Model Training**: The model is trained to predict food grades based on labeled datasets.
4. **Evaluation**: Accuracy and performance are assessed using metrics like accuracy score and confusion matrix.
5. **Deployment**: The model is exported and integrated into an API for the NutriRate app.

---

## Tools and Libraries
- **Python**
- **TensorFlow/Keras** - Neural network development
- **Scikit-learn** - Data preprocessing and model evaluation
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib & Seaborn** - Data visualization

---

## Sample Input
```json
{
  "protein": 2.0,
  "energy": 900.0,
  "fat": 20.0,
  "saturated_fat": 10.0,
  "sugars": 35.0,
  "fiber": 1.0,
  "salt": 1.5
}
```

## Sample Output
```json
{
    "grade": "B",
}
```

---

## Evaluation Metrics
The model is evaluated using:
- Accuracy Score
- Precision, Recall, and F1-Score
---

## Future Improvements
- Enhancing the dataset to include more diverse food items.
- Fine-tuning the model.
- Feature Engineering
- Using alternatives model like RandomForest and XGBoost.

---

## Contributors
- **Albertus Arga S**
- **Zaki Marsyandi**
- **Nishrina Khoirunnisa**
- Part of the Bangkit 2024 Capstone Project

---
