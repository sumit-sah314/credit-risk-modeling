Credit Risk Modeling

This project builds and evaluates machine learning models to predict the likelihood of credit default using classification algorithms. The final product is an interactive Streamlit app for visualizing and testing predictions:

Live App: https://credit-risk-modeling-zcog5pbrc3gshwhu2u35bp.streamlit.app/

------------------------------------------------------------

🚀 Goals

- Perform Exploratory Data Analysis (EDA) on credit datasets
- Train and evaluate models like:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Use model evaluation metrics:
  - ROC AUC
  - Confusion Matrix
  - Precision, Recall, F1 Score
- Handle class imbalance using:
  - SMOTE
  - Undersampling

------------------------------------------------------------

📦 Setup

Clone the Repository:

git clone https://github.com/sumit-sah314/credit-risk-modeling.git

Install Dependencies:

pip install -r requirements.txt

Run Locally:

streamlit run app/main.py

Make sure you have Python 3.8+ and pip installed.

------------------------------------------------------------

🌐 Live App

Try the deployed app here:  
https://credit-risk-modeling-zcog5pbrc3gshwhu2u35bp.streamlit.app/

------------------------------------------------------------

🗂 Project Structure

credit-risk-modeling/
├── app/
│   ├── main.py                  # Streamlit app
│   └── prediction_helper.py     # Model loading and prediction
├── artifacts/
│   └── model_data.joblib        # Trained model artifact
├── dataset/                     # Dataset(s)
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation

------------------------------------------------------------
🧠 ML Pipeline

1. Data cleaning & preprocessing
2. Feature engineering
3. Train-test splitting
4. Model training (with class balancing techniques)
5. Model evaluation & selection
6. Deployment on Streamlit Cloud

------------------------------------------------------------

📬 Contributions

Feel free to open issues or pull requests if you'd like to collaborate or improve this project.

------------------------------------------------------------

🧾 License

This project is open-source and free to use under the MIT License.
