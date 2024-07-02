# 💸 Loan Default Prediction with XGBoost
This repository contains a machine learning solution for predicting loan defaults, developed as part of a data science coding competition. The project utilizes the powerful XGBoost algorithm to build an accurate and reliable model, capable of identifying high-risk loan applications and enabling lenders to mitigate financial losses.
## 📝 Project Overview
The objective of this project was to develop a machine learning model that could accurately predict loan defaults based on various features such as income, credit score, employment details, and loan characteristics. By leveraging the XGBoost algorithm and employing advanced data preprocessing techniques, feature engineering, and hyperparameter tuning, the solution achieved a top-performing ROC-AUC score of 0.7595, outperforming 95% of the participants in the competition.

<img width="595" alt="Screenshot 2024-07-03 at 1 20 23 AM" src="https://github.com/ommagdum/Loan-Default-Prediction/assets/117524713/875e0f9a-7129-4791-8d3a-d831e5215d27">

## 🔑 Key Features
- **Data Preprocessing** : Performed log transformations on skewed numeric features, encoded categorical variables, and scaled numerical features for optimal model performance.
- **Hyperparameter Tuning** : Employed RandomizedSearchCV to perform a randomized search over a specified range of hyperparameters, optimizing the XGBoost model's performance on a cross-validation subset of the training data.
- **Iterative Refinement** : Continuously refined the model through multiple iterations, adjusting hyperparameters, and preprocessing techniques to improve performance.
- **Model Evaluation**: Evaluated the model's performance using appropriate metrics, such as the ROC-AUC score, on a held-out test set, ensuring robustness and reliability.
- **Deployment-Ready Solution**: Generated predicted probabilities for loan defaults on the test set, enabling seamless integration into lending processes and risk assessment workflows.

## 💼 Business Impact
An accurate loan default prediction model can significantly benefit lending institutions by:

- Mitigating financial risks associated with loan defaults.
- Improving risk management and decision-making processes.
- Enhancing profitability by optimizing loan portfolios and lending criteria.
- Streamlining the loan approval process and improving customer experience.
- Facilitating regulatory compliance by implementing robust risk assessment models.

## 🚀 Getting Started
To get started with this project, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/your-username/loan-default-prediction.git
   ```
2. Explore the Jupyter Notebook (LoanDefaultPrediction.ipynb) to understand the code and modeling process.
3. Run the notebook to preprocess the data, train the XGBoost model, and generate predictions.
4. Customize the solution as needed for your specific use case or dataset.

## 🤝 Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📜 License
This project is licensed under the MIT License.
