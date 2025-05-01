# Logistic Regression: Predicting Student Pass/Fail Outcome 🎓

This project demonstrates how to use Logistic Regression for binary classification. The goal is to predict whether a student will pass (1) or fail (0) based on the number of hours studied.

## 🔍 Problem Statement
Using a simple dataset of hours studied vs. pass/fail outcomes, the model learns to estimate the probability of passing using the sigmoid function.

## 🧠 Techniques Used
- Logistic Regression with `scikit-learn`
- Probability curve plotting with `matplotlib`
- Model evaluation using classification report

## 📊 Sample Output
- Predict whether a student who studied 5.5 hours will pass
- Visualize the decision boundary (0.5 threshold) on a sigmoid curve

## 📎 Applications
- Academic performance prediction
- Medical diagnosis (disease/no disease)
- Marketing (customer will buy/not buy)
- Spam classification

## 🛠 Tech Stack
- Python
- NumPy
- Matplotlib
- Scikit-learn

## 📷 Visualization
![image](https://github.com/user-attachments/assets/f84a7bbf-943f-44a7-96ed-66f55df6883b)

Insights:

1. The model predicts probability of Passing based on hours studied.
2. Increase in Porbability around 5 hours indicates that it is as threshold.
3. Decision boundary at 0.5, is around 5 hours. The students who studies above 5 hours are going to pass.
4. Considering the red dots, it seems the model is well fitted.




