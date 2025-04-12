# Bank Customer Churn Analysis & Machine Learning

This repository contains the full end-to-end process of solving a **Bank Customer Churn Prediction** problem using machine learning. This project was inspired by a **Kaggle competition I hosted**, where participants were challenged to build predictive models to identify customers likely to churn from a bank.

---

##  Project Objective

To predict whether a customer will churn or not based on their demographics and account activities, using historical data. Accurate predictions can help banks take proactive measures to retain valuable customers.

---

##  Project Structure

The main steps included in this repository are:

### 1. 🔍 Dataset Profiling
- Data description and column summaries
- Data types, missing values, duplicates
- Class balance assessment

### 2. 📊 Exploratory Data Analysis (EDA)
- Univariate and bivariate visualizations
- Insights into customer behavior
- Correlation analysis

### 3. 🛠️ Data Preprocessing
- Encoding categorical variables
- Dropping of irrelevant Columns
- Handling of Imbalance Class
- Feature engineering
- Train-test split

### 4. ⚙️ Model Building
- SMOTE used for balancing the target variable
- Multiple machine learning models tested (Logistic Regression, Random Forest, XGBoost, KNN & Decision Tree.)
- Hyperparameter tuning using `RandomizedSearchCV`


### 5. ✅ Model Evaluation
- M/L Models have the following ROC-AUC Score:
- Logistics Regression ROC-AUC Score: 0.8706
- Decision Tree ROC-AUC Score: 0.7734
- Random Forest ROC-AUC Score: 0.9256
- KNN ROC-AUC Score: 0.5720
- Xgboost ROC-AUC Score: 0.9261
- Best-performing models: Random Forest & XGBoost

### 6. 🚀 Model Deployment Preparation
- Streamlit integration setup
- Cleaned and serialized model with `joblib` and `pickle`
- Separated final files for deployment

---

## 📂 Files in This Repository

- `bank_churn_analysis.ipynb` – Main Jupyter Notebook for the entire process
- `data` – Contains original and cleaned datasets
- `models` – Saved machine learning models
- `images` – Visuals from EDA and model evaluation
- `README.md` – Project documentation

---

## 🌐 Live Demo

The deployment of the predictive model is available here:  
👉 [Streamlit App – Bank Customer Churn Prediction](https://bank-customer-churn-prediction-app-szvevdugbfdd8q6oghpuvj.streamlit.app/)

The app code and deployment setup can be found in the companion repository:  
🔗 [`bank-churn-streamlit-deployment`](https://github.com/FijabiAdekunle/bank-churn-streamlit-deployment)

---

## 🏁 Conclusion

This project demonstrates how machine learning can be applied to solve real-world customer churn challenges. It covers the full data science lifecycle from data profiling to model deployment.

---

## 🙌 Call to Action

Thanks for reviewing this end-to-end Machine Learning workflow on Bank Customer Churn Prediction!

- 🚀 Want to try the live model?  
  👉 [Launch the Streamlit App](https://bank-customer-churn-prediction-app-szvevdugbfdd8q6oghpuvj.streamlit.app/)

- 💻 Prefer code? Explore the app deployment setup here:  
  👉 [Streamlit Deployment Repo](https://github.com/FijabiAdekunle/bank-churn-streamlit-deployment)

- 🌐[View my full data analytics portfolio](https://sites.google.com/view/fijabijadekunle/home)

Feel free to fork this repo, try it on your data, and connect with me!


---

> “Navigating Data, Unveiling Insights, Driving Impact.”  
> — *FJ the Data Explorer*
