# Tiber-Cloud-Workshop
This project predicts loan prices using Logistic Regression, a machine learning model. It uses features such as loan amount, income, CIBIL score, and more to predict whether the loan price is likely to be approved or denied. The model is trained on a dataset with various financial parameters, and a Streamlit app is provided for users to interactively input their loan details to get predictions.

FEATURES: 
* Logistic Regression: Trains the model to predict loan approval.
* Loan Price Prediction: Users can input loan-related information and receive predictions on loan approval likelihood or price.
* Streamlit App: Easy-to-use web-based app to instantly get predictions.

REQUIREMENTS:
* Python
* Scikit-Learn (for Logistic Regression and KNN Regressor)
* Streamlit (for web app interface)
* Pandas (for data handling)
* NumPy (for array manipulation)
* Matplotlib and Seaborn (for data visualization)

DATASET COLUMNS:
* loan_id: Unique identifier for the loan.
* no_of_dependents: Number of dependents of the applicant.
* education: Education level of the applicant.
* self_employed: Whether the applicant is self-employed.
* income_annum: Annual income of the applicant.
* loan_amount: Amount of the loan applied for.
* loan_term: Term duration for the loan in years.
* cibil_score: Credit score of the applicant.
* residential_assets_value: Value of residential assets owned by the applicant.
* commercial_assets_value: Value of commercial assets owned by the applicant.
* luxury_assets_value: Value of luxury assets owned by the applicant.
* bank_asset_value: Value of bank assets held by the applicant.
* loan_status: Loan approval status (target variable).

STEPS IN THE PROJECT:
1. Data Preprocessing: The dataset includes both numeric and categorical columns, which are handled appropriately before training the model. StandardScaler is used to scale numeric features to improve model performance.
2. Model Creation & Training: A Logistic Regression model is trained using features such as loan amount, income, and credit score, along with additional asset values.
3. Prediction & Evaluation: The model predicts loan outcomes (approval or price) and evaluates performance using metrics like accuracy, mean squared error, and R² score.
4. Streamlit App: A user-friendly web app interface to input financial details (loan amount, interest rate, loan period) and receive loan predictions.

OUTPUT:
* Training Accuracy: 0.7611241217798594
* Mean Absolute Error: 0.2388758782201405
