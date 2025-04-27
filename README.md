# 💳 Credit Card Defaulter Prediction

This project predicts whether a customer will default on their credit card payment next month based on historical data.  
The goal is to help financial institutions minimize credit risk and make better lending decisions.

## 🚀 Features

- Supervised learning for binary classification (defaulter vs. non-defaulter)
- Data preprocessing, feature engineering, and exploratory data analysis (EDA)
- Model training using multiple algorithms
- Model evaluation with metrics like accuracy, precision, recall, and ROC-AUC
- Hyperparameter tuning to optimize model performance

## 🛠 Tech Stack

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Algorithms:** Logistic Regression, Random Forest, XGBoost
- **Other Tools:** Hyperparameter tuning (GridSearchCV)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-defaulter-prediction.git
   cd credit-card-defaulter-prediction
   ```

2.Create a virtual environment (optional but recommended):

   On Windows:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```
   On macOS/Linux:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```


4. Run the notebook:  
   Open the Jupyter Notebook or Python script to view and execute the code.

## 🧠 How It Works

- The dataset is first cleaned (handling missing values, encoding categorical variables).
- Exploratory Data Analysis (EDA) is performed to understand feature relationships.
- Features are selected and scaled for model readiness.
- Different machine learning models are trained and evaluated.
- The best-performing model is selected based on cross-validation scores.
- Finally, the model is tested on unseen data to evaluate real-world performance.

## 📊 Model Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Curve**

## 📂 Project Structure

```
credit-card-defaulter-prediction/
├── data/            # Dataset files
├── notebooks/       # Jupyter notebooks for development
├── src/             # Source code for preprocessing, training, evaluation
├── models/          # Saved machine learning models
├── requirements.txt # Python dependencies
└── README.md        # Project overview
```

## ✨ Future Improvements

- Deploy the model using Flask/Django into a web application.
- Implement real-time prediction API.
- Explore deep learning models for better accuracy.
- Perform feature importance analysis to explain predictions.
