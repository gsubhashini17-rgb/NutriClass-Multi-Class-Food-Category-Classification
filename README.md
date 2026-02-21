# NutriClass-Multi-Class-Food-Category-Classification

A machine learning project that classifies food items into 12 categories using nutritional attributes.
The project benchmarks multiple ML models and identifies the best-performing algorithm through structured evaluation.
________________________________________
Problem Statement
Food items vary significantly in nutritional composition.
The goal is to build a multi-class classification model that predicts the correct food category based on nutritional features such as:
•	Calories
•	Protein
•	Fat
•	Saturated Fat
•	Fiber
•	Carbohydrates
•	Grams
________________________________________
📊 Dataset Overview
•	🔢 Total Samples: 335
•	🎯 Target Classes: 12 food categories
•	🧹 Data Cleaning:
o	Removed comma-separated numeric values
o	Converted trace values
o	Handled missing data
o	Merged similar food categories
•	Feature Scaling applied for ANN, SVM, and KNN
________________________________________
⚙️ Models Implemented
This project benchmarks 7 classification algorithms:
•	Logistic Regression
•	K-Nearest Neighbors (KNN)
•	Support Vector Machine (SVM)
•	Random Forest
•	Gradient Boosting
•	XGBoost
•	Artificial Neural Network (MLPClassifier)
Hyperparameter tuning performed using GridSearchCV
________________________________________
📈 Model Performance
Model	Accuracy
Random Forest	84.8%
ANN (MLP)	75.7%
Gradient Boosting	69.7%
KNN	66.7%
XGBoost	65.7%
Logistic Regression	63.6%
SVM	56.0%
🏆 Best Performing Model: Random Forest (84.8% Accuracy)
________________________________________
🔍 Feature Importance (Random Forest)
Top influential features:
1.	Carbohydrates
2.	Grams
3.	Protein
4.	Fat
5.	Saturated Fat
6.	Fiber
7.	Calories
Carbohydrates emerged as the most significant predictor in determining food categories.
________________________________________
🧠 Key Insights
•	Ensemble methods outperformed linear models.
•	Random Forest generalized best on structured tabular data.
•	ANN performed well after feature scaling.
•	Nutritional attributes provide strong class separability.
________________________________________
🛠 Tech Stack
•	Python
•	NumPy & Pandas
•	Scikit-learn
•	XGBoost
•	Matplotlib / Seaborn
________________________________________
🔮 Future Improvements
•	📈 Increase dataset size
•	🤖 Deep Neural Networks
•	🔗 Model stacking / ensemble blending
•	🌐 Deploy via Streamlit
