# 📊 Loan Approval Prediction (R & RPubs)

> A statistical and machine learning analysis to predict loan approval outcomes using R, published via RPubs.

## 🧠 Project Overview

This project explores key factors influencing loan approval decisions and builds predictive models to assess the likelihood of approval. Using R and relevant libraries, it combines exploratory data analysis, statistical testing, and predictive modeling to support credit risk assessment.

The full report is available here:  
👉 [Loan Approval Prediction – RPubs](https://rpubs.com/psb23114952/1322734)

---

## 🎯 Objectives

1. **Explore** the dataset to understand borrower and loan characteristics.
2. **Identify** variables strongly correlated with loan approval.
3. **Train** classification models (e.g., logistic regression, decision trees, random forests).
4. **Evaluate** model performance using accuracy, precision, recall, F1-score, and ROC AUC.
5. **Provide** recommendations for credit decision-making.

---

## 📋 Dataset & Features

While the RPubs report provides all dataset details, typical variables include:

- **Applicant information**: `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`, `Credit_History`
- **Loan details**: `LoanAmount`, `Term`, `Property_Area`, `Loan_Status` (target)

---

## 🔍 Exploratory Analysis Highlights

- Visualized loan outcomes by gender, education, and employment status.
- Identified patterns in credit history and property area influencing approvals.
- Report features descriptive plots and summary statistics.

---

## 📈 Modeling**

- Built classification models (e.g., logistic regression, decision trees).
- Used cross-validation to ensure robust performance metrics.
- Plotted ROC curves and confusion matrices to compare models.

---

## 💡 Key Insights

- **Strong predictors**: Consistent credit history and higher income levels.
- **Model performance**: Certain models achieved strong predictive accuracy (*details in RPubs*).
- **Actionable findings**: Recommendations for credit approval criteria based on model insights.

---

## 🛠️ How to Access the Analysis

- **View** the full interactive report on RPubs:  
  https://rpubs.com/psb23114952/1322734

- **Reproduce the analysis**:
  1. Download the R Markdown (`.Rmd`) notebook from RPubs (optionally via GitHub).
  2. Render locally in RStudio using:
     ```r
     rmarkdown::render("Loan_Approval_Prediction.Rmd")
     ```

---

## 📁 Repository Contents

- `Loan_Approval_Prediction.Rmd` – R Markdown file with full analysis.
- `data/loan_data.csv` – Dataset used in the analysis.
- `README.md` – This project overview.

---

## 👩‍💻 Contributor

- Puteri Balqis, Anis Insyirah, Yuhan, Izzati, Adibah

---

## 📌 Future Enhancements

- Hyperparameter tuning (e.g., grid search on random forest).
- Feature engineering (e.g., income-to-loan ratios).
- Deploy as a Shiny dashboard for interactive model exploration.
