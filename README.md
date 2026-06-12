# 📧 SMS Spam Classification using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to classify SMS messages as **Spam** or **Ham (Not Spam)**.

The model is trained on the SMS Spam Collection Dataset and uses **TF-IDF Vectorization** along with the **Multinomial Naive Bayes** algorithm for text classification.

---

## 🎯 Objective

To build a machine learning model that can automatically identify whether a message is spam or not.

---

## 🛠 Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Multinomial Naive Bayes
* Matplotlib
* Seaborn
* Google Colab

---

## 📂 Dataset

SMS Spam Collection Dataset

* Total Messages: 5,572
* Classes:

  * Ham (Not Spam)
  * Spam

---

## ⚙️ Project Workflow

1. Load the dataset
2. Explore and understand the data
3. Convert labels into numerical values
4. Split the dataset into training and testing sets
5. Convert text into numerical features using TF-IDF
6. Train the model using Multinomial Naive Bayes
7. Evaluate the model using various metrics
8. Save the trained model and vectorizer

---

## 📊 Model Performance

### Classification Report

| Class    | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| Ham (0)  | 0.96      | 1.00   | 0.98     |
| Spam (1) | 1.00      | 0.75   | 0.86     |

### Overall Results

* Accuracy: 96.68%
* Macro Average F1-Score: 0.92
* Weighted Average F1-Score: 0.96

---

## 📈 Evaluation Metrics Used

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📁 Project Structure

SMS-Spam-Classifier/

├── spam_classification.ipynb

├── spam_classification.py

├── spam_classifier.pkl

├── tfidf_vectorizer.pkl

├── requirements.txt

├── README.md

└── screenshots/

---

## 🚀 Future Improvements

* Try Logistic Regression
* Try Random Forest Classifier
* Build a Streamlit Web Application
* Deploy the model online
* Improve spam detection recall

---

## 📚 What I Learned

Through this project, I learned:

* Supervised Learning
* Classification
* Train-Test Split
* TF-IDF Vectorization
* Naive Bayes Algorithm
* Accuracy, Precision, Recall and F1-Score
* Confusion Matrix
* Saving and Reusing Trained Models
* GitHub Project Management

---

## 👩‍💻 Author

Arthi Saran

First Machine Learning Classification Project 🚀
