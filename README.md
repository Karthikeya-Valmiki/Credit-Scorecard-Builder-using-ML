# Credit Scorecard Builder using Machine Learning

This repository contains a comprehensive guide to building a robust credit scorecard using machine learning techniques. The project demonstrates an end-to-end process for credit risk modeling, covering essential steps from data preprocessing and model development to scorecard generation and performance optimization. The primary goal is to provide a structured and practical approach to developing credit risk scorecards, ensuring interpretability, accuracy, and business alignment.

## **Dataset**
The project uses the **"uci-credit-card-data"** dataset, which contains anonymized credit card information, including demographic and transactional data. This dataset is used to train, validate, and evaluate the credit risk models.

---

## **Project Steps**
1. **Feature Filtering**: Identifying and selecting the most relevant features for modeling.
2. **Feature Binning**: Grouping continuous variables into bins to enhance interpretability.
3. **Transform to WOE (Weight of Evidence)**: Converting features into WOE format for better alignment with logistic regression.
4. **Calculate PSI (Population Stability Index)**: Measuring data stability over time.
5. **Output IV (Information Value)**: Evaluating the predictive power of each feature.
6. **Model Tuning**: Optimizing model hyperparameters for improved performance.
7. **Logistic Regression**: Building an interpretable baseline model.
8. **GBDT Model**: Utilizing Gradient Boosted Decision Trees for advanced modeling.
9. **Model Production**: Preparing models for deployment.
10. **Scorecard Generation**: Translating model outputs into a user-friendly credit scorecard format.
11. **Distribution Analysis**: Assessing the separation between good and bad credit risks.
12. **Threshold Tuning**: Optimizing thresholds to balance risk and coverage.
13. **Threshold Tuning & Trade-off Analysis**: Balancing loss and coverage to align with business goals.

---

## **Repository Contents**
- **`Main notebook/`**: Contains the Jupyter Notebook(s) with detailed implementation of all project steps.
- **`csv file`**: Directory for the "uci-credit-card-data" dataset.
- **`README.md`**: This readme file, explaining the project structure and details.
- **`LICENSE`**: License file

---

## **How to Use**
1. Clone this repository:
   ```bash
   git clone https://github.com/Karthikeya-Valmiki/Credit-Scorecard-Builder-using-ML.git


## Created by - Karthikeya Valmiki
