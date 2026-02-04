# House-Price-Prediction
Machine Learning project to predict house prices using Linear Regression, Decision Tree, Random Forest, and XGBoost with hyperparameter tuning.

# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting house prices using multiple machine learning regression models.  
The goal is to compare different models, apply cross-validation and hyperparameter tuning, and select the best-performing model for accurate house price prediction.

---

## 🎯 Problem Statement
Accurately predicting house prices is crucial for buyers, sellers, and real estate companies.  
This project aims to build a reliable regression model that can predict house prices based on various features.

---

## 🧠 Models Used
The following machine learning models were implemented and evaluated:

1. Linear Regression (Baseline Model)  
2. Decision Tree Regressor  
3. Random Forest Regressor  
4. XGBoost Regressor (Final Model) ✅  

Each model was evaluated using standard regression metrics and improved using hyperparameter tuning.

---

## 📊 Evaluation Metrics
The models were evaluated using:

- R² Score – Measures how well the model explains variance in house prices  
- RMSE (Root Mean Squared Error) – Penalizes large prediction errors  
- MAE (Mean Absolute Error) – Measures average absolute prediction error  

---

## 🧪 Cross-Validation & Hyperparameter Tuning
- 5-Fold Cross-Validation was applied to ensure model stability  
- GridSearchCV was used for hyperparameter tuning  
- Performance before and after tuning was compared  

---

## 🏆 Best Model Selection
After comparing all models, Tuned XGBoost Regressor was selected as the final model because:
- Highest R² Score
- Lowest RMSE & MAE
- Better generalization performance on unseen data

---

## 🚀 Model Deployment (Future Work)
The final tuned XGBoost model was saved using joblib for deployment purposes.

- Model file: xgboost_house_price_model.pkl
- The saved model was reloaded and tested on unseen data as a sanity check

This ensures the model is production-ready and can be deployed on a live server.

---

## 📁 Project Files
- House Price Pred.ipynb – Complete notebook with data processing, modeling, and evaluation  
- xgboost_house_price_model.pkl – Trained final model  
- README.md – Project documentation  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  

---

## 📌 Conclusion
This project demonstrates a complete end-to-end machine learning workflow, from data preprocessing to model deployment.  
The results show that advanced ensemble models like XGBoost significantly outperform traditional regression techniques in house price prediction tasks.

---

## 🔗 GitHub Repository
👉 https://github.com/kabilesh-coder/House-Price-Prediction
