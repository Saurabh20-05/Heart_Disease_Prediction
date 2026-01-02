❤️ Heart Disease Prediction using Logistic Regression

This project uses **Logistic Regression** to predict whether a person has **heart disease or not** based on medical attributes.
The model is trained on a structured dataset (`heart_disease_data.csv`) containing clinical parameters related to heart health.

---

📘 Project Overview

This is a **Machine Learning–based binary classification project**.
By analyzing a patient’s medical data such as age, cholesterol level, blood pressure, and other health indicators, the model determines whether the person is likely to have heart disease.

The goal is to build a **simple, interpretable, and efficient heart disease prediction system** using Logistic Regression.

---

🗂️ Dataset Information

- **Dataset Name:** Heart Disease Dataset  
- **Format:** CSV file (`heart_disease_data.csv`)  
- **Target Column:** `target`  

### Target Labels
- `1` → Defective Heart  
- `0` → Healthy Heart  

All other columns are treated as **input features**.

---

🧠 Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  

---

⚙️ Project Workflow

1. Import required libraries  
2. Load the dataset using Pandas  
3. Explore the dataset (shape, info, statistics)  
4. Check for missing values  
5. Analyze target variable distribution  
6. Separate **features (X)** and **target (Y)**  
7. Split the data into:
   - 80% Training Data  
   - 20% Testing Data  
8. Train the model using **Logistic Regression**  
9. Evaluate the model using **accuracy score**  
10. Build a predictive system for new input data  

---

📊 Model Performance (Example)

- **Accuracy on Training Data:** ~85%  
- **Accuracy on Testing Data:** ~82%  

(Accuracy may vary depending on data split and environment)

---

🧪 Predicting Custom Input

You can modify this variable inside the code:

input_data = (70,1,0,145,174,0,1,125,1,2.6,0,0,3)

The model will output either:

- The person has heart disease
or
- The person does not have a heart disease

---

👨‍💻 Author

Developed by Saurabh
Feel free to connect or contribute to this project!

⭐ If you found this project helpful, don’t forget to star the repository!
