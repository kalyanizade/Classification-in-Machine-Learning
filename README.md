# 🔍 Logistic Regression Classification Web App

## 📖 Project Explanation

The **Logistic Regression Classification Web App** is a machine learning application developed using **Python**, **Streamlit**, and **Scikit-learn**. The purpose of this project is to demonstrate how Logistic Regression can be used to solve binary classification problems through an interactive web interface.

The application allows users to upload their own CSV dataset and automatically performs the complete machine learning workflow, including data preprocessing, model training, prediction, and performance evaluation.

After uploading the dataset, the application extracts the required features and target variable, splits the data into training and testing sets, and applies **StandardScaler** to normalize the feature values. A **Logistic Regression** model is then trained using the training data.

Once the model is trained, it predicts the class labels for the testing dataset and evaluates the model using several performance metrics. The application displays a **Confusion Matrix**, **Accuracy Score**, **Classification Report** (including Precision, Recall, and F1-Score), **Training Accuracy (Bias)**, **Testing Accuracy (Variance)**, **ROC Curve**, and **AUC (Area Under the Curve) Score**.

The Streamlit interface provides an easy-to-use dashboard where users can visualize the model's performance without writing any additional code. This project is ideal for beginners who want to understand the complete implementation of Logistic Regression along with important evaluation metrics used in classification problems.

---

## 🚀 Features

- 📂 Upload your own CSV dataset
- 👀 Preview uploaded dataset
- 🤖 Train Logistic Regression model
- 📊 Display Confusion Matrix
- 📈 Calculate Accuracy Score
- 📄 Generate Classification Report
- 🎯 Display Training Accuracy (Bias)
- 📉 Display Testing Accuracy (Variance)
- 📌 Calculate AUC Score
- 📈 Plot ROC Curve
- ⚡ Interactive Streamlit interface

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
---

## ▶️ Run the Project

Run the Streamlit application

```bash
streamlit run "logit deployment.py"
```

The application will open in your browser.

---

## 📊 Model Workflow

1. Upload a CSV dataset.
2. Select features and target.
3. Split the dataset into training and testing sets.
4. Standardize the features.
5. Train the Logistic Regression model.
6. Make predictions.
7. Display:
   - Confusion Matrix
   - Accuracy Score
   - Classification Report
   - Bias (Training Accuracy)
   - Variance (Testing Accuracy)
   - ROC Curve
   - AUC Score

---

## 📸 Output

The application displays:

- Dataset Preview
- Confusion Matrix Heatmap
- Accuracy Score
- Classification Report
- Training Accuracy
- Testing Accuracy
- ROC Curve
- AUC Score

---

## 📚 Machine Learning Concepts Used

- Logistic Regression
- Binary Classification
- Feature Scaling
- Train-Test Split
- Confusion Matrix
- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC Curve
- AUC Score
---

## 👩‍💻 Author

**Kalyani Zade**

- MCA Graduate
- Python Developer
- Machine Learning Enthusiast

---
