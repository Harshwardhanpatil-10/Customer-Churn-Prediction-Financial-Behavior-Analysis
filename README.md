# Customer-Churn-Prediction-Financial-Behavior-Analysis


An end-to-end Machine Learning project that analyzes customer financial behavior and predicts churn risk using advanced ML techniques such as **XGBoost, Optuna hyperparameter tuning, MLflow experiment tracking, and Decile & Lift analysis**.

This project simulates a **real-world industry ML pipeline** used by data science teams to identify customers likely to churn and enable proactive retention strategies.

---

## 📌 Project Objective

Customer churn is a major challenge for businesses because acquiring a new customer costs significantly more than retaining an existing one.

The objective of this project is to:

- Analyze customer financial behavior
- Identify patterns leading to churn
- Build a predictive machine learning model
- Evaluate performance using **business-driven metrics**

---

## 🚀 Key Features

- End-to-End Machine Learning Pipeline  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Stratified Train-Test Splitting  
- Model Training & Evaluation  
- Hyperparameter Optimization using **Optuna**  
- Experiment Tracking using **MLflow**  
- Business Metrics Evaluation using **Decile Analysis & Lift**

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading & Inspection

- Dataset imported and inspected
- Data types validated
- Missing values identified

---

### 2️⃣ Data Cleaning

- Converted invalid values (such as `"na"`) into proper `NaN`
- Handled missing values
- Ensured consistent data formats

---

### 3️⃣ Exploratory Data Analysis (EDA)

Exploratory analysis performed to understand:

- Feature distributions
- Customer behavior patterns
- Correlation between variables
- Potential predictive signals

---

### 4️⃣ Feature Engineering

Created meaningful features to improve model performance, including:

- Customer financial behavior indicators
- Aggregated metrics
- Encoded categorical variables

---

### 5️⃣ Data Preprocessing Pipeline

Implemented **Scikit-Learn preprocessing pipelines** to automate:

- Missing value imputation
- Feature scaling
- Categorical encoding
- Feature transformation

This ensures the workflow is **reproducible and production-ready**.

---

### 6️⃣ Train-Test Split

Used **StratifiedShuffleSplit** to maintain class distribution between training and testing datasets.

This is important because churn datasets are often **imbalanced**.

---

### 7️⃣ Model Training

Multiple machine learning models were trained and evaluated:

- Logistic Regression
- Random Forest
- XGBoost

---

### 8️⃣ Hyperparameter Optimization

Used **Optuna**, an automatic hyperparameter optimization framework, to identify the best model configuration.

Benefits:

- Efficient search of parameter space
- Improved model performance
- Faster optimization process

---

### 9️⃣ Experiment Tracking with MLflow

MLflow was used to track:

- Model parameters
- Evaluation metrics
- Experiment runs
- Model comparison

This ensures **experiment reproducibility and model governance**.

---

### 🔟 Model Evaluation

Model performance was evaluated using both **statistical and business-focused metrics**:

- AUC Score
- Cross Validation Score
- Decile Analysis
- Lift Analysis

---

## 📊 Business Insight: Decile & Lift Analysis

Traditional metrics like accuracy do not always represent real business value.

Therefore, **Decile Analysis and Lift Charts** were used to evaluate how effectively the model identifies high-risk customers.

Benefits:

- Identify top churn-risk customer segments
- Prioritize retention campaigns
- Improve marketing ROI

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Optuna
- MLflow
- Matplotlib
- Seaborn

---

## 📈 Key Learning Outcomes

Through this project I strengthened my understanding of:

- Designing production-style ML pipelines
- Feature engineering for behavioral analytics
- Hyperparameter tuning using Optuna
- Experiment tracking with MLflow
- Business-oriented model evaluation using Decile & Lift

---

## 🔮 Future Improvements

Potential enhancements include:

- Deploying the model using **FastAPI / Flask**
- Building an interactive **Streamlit dashboard**
- Creating automated **ML retraining pipelines**
- Adding **real-time churn prediction API**

---

## 👨‍💻 Author

**Harshvardhan Patil**

Aspiring Data Scientist | AI/ML Enthusiast

