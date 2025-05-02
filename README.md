# 💳 Predicting Loan Default Risk with Logistic Regression (Lending Club Data)

## 🧠 Real-World Problem

Peer-to-peer lending platforms like Lending Club must assess the creditworthiness of borrowers to reduce loan defaults. This project builds a **logistic regression model** to classify whether a loan will default, using borrower information such as income, loan amount, and credit history.

---

## 🔍 What This Project Does

- Preprocesses and cleans Lending Club loan data
- Applies logistic regression to model the binary outcome of **loan default**
- Evaluates model performance using:
  - **Confusion matrix**
  - **ROC Curve**
  - **Precision-Recall Curve**
  - **F1 Score**
- Interprets model coefficients to understand key drivers of default risk

---

## 📁 Project Structure

```
.
├── Workshop_rmd_London_house_Prices_post.Rmd   # Source R Markdown code
├── eviction_classifier.html                     # Exported HTML report
├── README.md                                    # Project documentation
```

---

## 🛠 Tools & Technologies

- **Language**: R
- **Packages Used**: `tidyverse`, `glm`, `pROC`, `yardstick`, `caret`, `gt`, `ROCR`
- **Model**: Logistic Regression (Binary Classification)

---

## 📊 Key Results

- Achieved an **AUC of ~0.75**, indicating reasonable model performance
- Precision-Recall tradeoff analyzed to optimize threshold selection
- Identified top predictors of loan default: **annual income**, **debt-to-income ratio**, and **loan grade**

---

## 🚀 How to Run

1. Clone the repo and open `Workshop_rmd_London_house_Prices_post.Rmd` in RStudio
2. Knit the file to HTML (`eviction_classifier.html`) to reproduce the full output
3. Install any missing packages using:
   ```r
   install.packages(c("tidyverse", "gt", "pROC", "caret", "yardstick"))
   ```



