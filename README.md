🔍 Phase 3 – Feature Selection & Hyperparameter Tuning
Project: Bank Marketing Campaign Analysis

🎯 Objective:
Select the most relevant features influencing customer behavior.

Optimize model performance using Grid Search with Cross-Validation.

Identify the best-performing classifier and regressor based on evaluation metrics.

📂 Dataset:
File used: bank-full-processed.csv

Target Variables:

Classification → y (Term deposit subscription: yes/no)

Regression → balance (Customer account balance)

🔧 Key Steps:
✅ 1. Feature Selection
Used Random Forest models to compute feature importances.

Selected top features based on their contribution to model performance.

Feature selection helps reduce overfitting and improves interpretability.

✅ 2. Hyperparameter Tuning (Grid Search)
Used GridSearchCV with 5-fold cross-validation to tune hyperparameters for both models:

Best parameters selected using grid search.

Evaluated using confusion matrix and accuracy.

Regressor Tuning: RandomForestRegressor

Evaluated using R² score for prediction accuracy.

📈 Evaluation Metrics:

🧠 Classification:
Best Parameters: Displayed after Grid Search.

Confusion Matrix: Plotted using ConfusionMatrixDisplay.

Accuracy: Assessed using test predictions.

📊 Regression:
Best Parameters: Displayed after Grid Search.

R² Score: Used to evaluate model fit on test data.

✅ Output Summary:
Final optimized models saved for deployment.

Feature importance helped in selecting relevant attributes.

Confusion matrix and R² score used to validate model effectiveness.

