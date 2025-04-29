# spam-sms-detection
A machine learning model that detects spam SMS messages
# 📱 Spam SMS Detection using Machine Learning

This project aims to build a machine learning model that can accurately classify SMS messages as **spam** or **ham (not spam)** using Natural Language Processing (NLP) and a Naive Bayes classifier.

---

## 🧠 Objective
To detect and filter spam messages using a trained model based on SMS text data.

---

## 📁 Dataset
- **Source**: [UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- **Format**: CSV file with two columns:
  - `v1`: Label (spam or ham)
  - `v2`: SMS message text

---

## 📊 Technologies & Libraries Used
- Python
- pandas, numpy
- scikit-learn
- nltk
- matplotlib, seaborn

---

## 🔄 Workflow Steps

1. **Import the dataset**
2. **Clean and preprocess** the text
3. **Vectorize** text using TF-IDF
4. **Train a classifier** using Naive Bayes
5. **Evaluate** the model

---

## 📌 How to Run This Project (Colab Recommended)

1. Open the `spam_detection.ipynb` file in [Google Colab](https://colab.research.google.com/)
2. Upload the `spam.csv` file when prompted
3. Run all cells step-by-step
4. View accuracy, confusion matrix, and classification report

---

## 📈 Output Example

- Accuracy Score: 97%+
- Confusion Matrix:

