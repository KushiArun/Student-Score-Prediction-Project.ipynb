
# Student Score Prediction

A simple machine learning project that predicts a student's exam percentage score based on the number of hours they studied.

---

## Project Overview

- *Type:* Supervised Learning – Regression  
- *Algorithm Used:* Linear Regression  
- *Dataset:* Student study hours vs. scores  
- *Tools:* Python, Pandas, Scikit-learn, Matplotlib  
- *Evaluation Metrics:* Mean Squared Error (MSE), R² Score  

---

## Dataset Description

The dataset consists of two columns:  
- *Hours:* Number of hours a student studied  
- *Scores:* Percentage score achieved by the student

Sample data:

| Hours Studied | Percentage Score |
|---------------|------------------|
| 2.5           | 21               |
| 5.1           | 47               |
| 3.2           | 27               |
| ...           | ...              |

---

## Steps Implemented

1. Loaded dataset from CSV  
2. Visualized data with scatter plot  
3. Split data into training and testing sets  
4. Trained a Linear Regression model  
5. Evaluated model performance using MSE and R² score  
6. Visualized regression line with test data  
7. Predicted scores for custom input study hours

---

## Sample Usage

```python
hours = 9.25
predicted_score = model.predict([[hours]])
print(f"Predicted score for studying {hours} hours: {predicted_score[0]:.2f}")


---

How to Run

1. Open the Jupyter Notebook or Google Colab file.


2. Run the cells step-by-step to train the model and make predictions.


3. Modify the sample input to predict scores for different study hours.




---

Author

Kushi A.
B.E. in Artificial Intelligence & Data Science
East West Institute of Technology


---

Dataset Source

The dataset used in this project is publicly available at:
Student Scores Dataset
