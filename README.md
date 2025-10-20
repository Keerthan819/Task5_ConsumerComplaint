# Task 5 - Consumer Complaint Text Classification

**Name:** Keerthan D  
**Date:** 20-Oct-2025  

---

## Task Description
This task performs text classification on the Consumer Complaint database to classify complaints into 4 categories:

0. Credit reporting, repair, or other  
1. Debt collection  
2. Consumer Loan  
3. Mortgage  

The goal is to preprocess complaint text, extract features, train multiple models, evaluate them, and predict new complaints.

---

## Dataset
[Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)

---

## Steps Followed
1. **Load Dataset**: Selected `Product` and `Consumer complaint narrative` columns, removed missing values.  
2. **Exploratory Data Analysis (EDA)**: Plotted category distribution to understand dataset balance.  
3. **Text Preprocessing**: Converted text to lowercase, removed punctuation, and removed stopwords.  
4. **Feature Engineering**: Applied TF-IDF vectorization to convert text into numerical features.  
5. **Model Selection**: Trained three models:
   - Naive Bayes  
   - Logistic Regression  
   - Random Forest  
6. **Model Comparison**: Checked accuracy of all models and selected the best-performing one.  
7. **Model Evaluation**: Generated classification report and confusion matrix for the best model.  
8. **Prediction**: Created a function to classify new complaints into one of the 4 categories.

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Task5_ConsumerComplaint_TextClassification_Keerthan.git
