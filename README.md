import os

# -------------------------------
# 1. Project Information (edit these if needed)
# -------------------------------
project_title = "Disease Prediction using Machine Learning"
project_description = "This project is a Disease Prediction System built in Google Colab that uses machine learning models to predict diseases based on symptoms provided by the user."

features = [
    "Preprocessing of symptom-based dataset",
    "Training and evaluation of machine learning models (Decision Tree, Random Forest, Naive Bayes, etc.)",
    "Interactive prediction of diseases based on input symptoms",
    "Performance analysis using accuracy, confusion matrix, and classification report",
    "Deployed and tested in Google Colab"
]

models_used = [
    "Decision Tree Classifier",
    "Random Forest Classifier",
    "Naive Bayes",
    "Support Vector Machine (SVM)"
]

accuracy = "XX%"  # 🔹 Replace with actual accuracy after training

# -------------------------------
# 2. Generate README.md Content
# -------------------------------
readme_content = f"""# 🩺 {project_title}

{project_description}  

## 📌 Features
""" + "\n".join([f"- {f}" for f in features]) + """

## 📂 Project Structure
