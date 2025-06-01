# 💼 Bank Churn Prediction Using Machine Learning

This project explores the use of machine learning to predict customer churn in the banking sector, enabling financial institutions to identify customers likely to leave and take proactive measures to improve retention.

## 📊 Objectives

* Predict customer churn using real-world banking data
* Compare performance across multiple ML algorithms
* Identify key features influencing churn behaviour
* Provide actionable insights for retention strategies

## 🧠 Models Applied

* XGBoost
* Random Forest
* Decision Tree
* Logistic Regression

## 🛠️ Workflow

1. **Data Preprocessing**: Cleaning, encoding, scaling
2. **Exploratory Data Analysis (EDA)**: Understanding trends and patterns
3. **Feature Selection**: Identifying most predictive variables
4. **Model Training & Tuning**: Using cross-validation and hyperparameter optimization
5. **Evaluation**: Based on accuracy, AUC, precision, recall, and F1-score
6. **Feature Importance Analysis**: Understanding which features drive churn

## 📈 Key Findings

* **XGBoost** delivered the highest training accuracy (95.98%) and a robust test accuracy (84.24%), showing strong generalization and ability to handle complex patterns.
* **Random Forest** and **Decision Tree** achieved comparable results with solid interpretability and performance.
* **Logistic Regression** offered baseline insights but struggled with the non-linearity of churn prediction.
  
- **Top predictors:** Number of products, customer activity status, geography, balance, age, and gender.

## 💡 Insights

* Ensemble methods (XGBoost, Random Forest) outperform simpler models and handle class imbalance more effectively.
* Model interpretability (via feature importance) is crucial for stakeholders.
* Churn is multi-dimensional-  driven by behaviour, demographics, and engagement.

## ✅ Recommendations

* Banks should deploy ensemble models like XGBoost for real-time churn detection.
* Focused marketing strategies should be developed based on identified key churn drivers.
* Continuously update and validate models to reflect changing customer behavior.

## 🔮 Future Work

* Experiment with deep learning architectures (e.g., DNNs) to capture complex interactions.
* Incorporate behavioral and transactional data for richer context.
* Explore SHAP or LIME for enhanced model explainability.

## 🚀 How to Run

1. Clone the repo:
   `git clone https://github.com/iam-larra/Customer-Churn-Prediction.git`
2. Install requirements:
   `pip install -r requirements.txt`
3. Run Jupyter Notebook to explore and execute the pipeline.
