# Task 5 - Consumer Complaint Text Classification

**Name:** Keerthan D  
**Date:** 20-Oct-2025  

---

## Task Description
This task performs **text classification** on the Consumer Complaint Database. The goal is to classify consumer complaints into the following categories:

0. Credit reporting, repair, or other  
1. Debt collection  
2. Consumer Loan  
3. Mortgage  

The task involves preprocessing the complaint text, feature extraction, training multiple machine learning models, evaluating their performance, and predicting new complaints.

---

## Dataset
[Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)

---

## Steps Followed
1. **Load Dataset:** Selected relevant columns (`Product` and `Consumer complaint narrative`) and removed missing values.  
2. **Exploratory Data Analysis (EDA):**  
   - Plotted the distribution of complaint categories to check class balance.  
3. **Text Preprocessing:**  
   - Converted text to lowercase  
   - Removed punctuation  
   - Removed stopwords using NLTK  
4. **Feature Engineering:**  
   - Used TF-IDF vectorization to convert text into numerical features.  
5. **Model Selection & Training:**  
   - Trained three classifiers:  
     - Naive Bayes  
     - Logistic Regression  
     - Random Forest  
6. **Model Comparison:**  
   - Compared accuracy of all models and selected the best-performing model.  
7. **Model Evaluation:**  
   - Generated classification report with Precision, Recall, F1-score  
   - Plotted confusion matrix  
8. **Prediction:**  
   - Created a function `predict_complaint(text)` to classify new complaints into one of the 4 categories.  

---

## How to Run

1. **Download the Notebook**
   - Download or fork the repository from GitHub:  
     [Task5_ConsumerComplaint](https://github.com/Keerthan819/Task5_ConsumerComplaint)

2. **Install Required Libraries**
   - Make sure you have Python 3.x installed.
   - Install the required Python packages
