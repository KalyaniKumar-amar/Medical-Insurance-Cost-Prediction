# Medical-Insurance-Cost-Prediction
Predicting individual medical insurance costs based on demographic and health data using Machine Learning models.
# 🏥 Medical Insurance Cost Prediction

Predicting individual medical insurance charges based on demographic and health-related factors using Machine Learning models.

---

## 📌 Objective

- Analyze health insurance data.
- Build predictive models to estimate insurance charges.
- Deploy an interactive web app for users to predict their own charges.

---

## 🧩 Dataset Overview

- **Features:**
  - Age
  - Sex
  - BMI (Body Mass Index)
  - Number of Children
  - Smoker Status
  - Region
- **Target:**
  - Charges (Medical Insurance Cost)

Dataset Source: [Kaggle - Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

## 🔥 Workflow

1. **Data Loading & Exploration**  
   - Summary statistics, missing values check, visualization.

2. **Data Preprocessing**  
   - Encoding categorical features.
   - Scaling numerical features.

3. **Model Building**  
   - Linear Regression (baseline)
   - Random Forest Regressor
   - Gradient Boosting Regressor

4. **Model Evaluation**  
   - R² Score, Mean Squared Error.
   - Scatter plot of Actual vs Predicted charges.

5. **Deployment**  
   - Built a **Streamlit app** to interactively predict insurance costs.

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit
- **Tools:** Jupyter Notebook, Streamlit

---

## 📈 Results

- Smoking status, age, and BMI are key factors influencing charges.
- Ensemble models (Random Forest, Gradient Boosting) outperform simple Linear Regression.



