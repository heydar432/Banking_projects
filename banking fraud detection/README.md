# Credit Card Fraud Detection Analysis

Analyzing and predicting credit card fraud using machine learning techniques.

## 📚 Dataset

The dataset for this project is sourced from Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It comprises various anonymized features along with a 'Class' feature indicating fraud.

## 🧮 Data Preprocessing

- Data is rebalanced due to the disproportionate class distribution.
- Duplicates are removed to ensure data integrity.
- Correlation analysis is conducted to select the most relevant features.

## 🔍 Model Selection and Training

- A range of models, including XGBoost, are experimented with.
- Feature selection is performed using forward elimination from 7 to 12 features.
- Optimum feature count is determined based on F1 score and accuracy.

## 🏆 Model Evaluation

- Models are evaluated on accuracy and F1 score.
- Grid Search CV is applied to fine-tune the XGBoost model.
- Best parameters are identified and the model is retrained.

## 📈 Results

- The XGBoost model with optimized hyperparameters showed promising results.
- F1 score and accuracy are reported for the final model.

## 🛠️ Tools Used

- Python libraries: NumPy, Pandas, XGBoost, Scikit-Learn.
- Metrics: Accuracy, Precision, Recall, F1 Score.
- Techniques: Grid Search, Feature Selection, Correlation Analysis.

## 💡 Key Observations

- The rebalanced dataset helped in improving the model's performance.
- Feature selection and hyperparameter tuning were crucial in enhancing the model's accuracy and F1 score.

