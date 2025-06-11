
# 📧 Spam Detection using Naive Bayes

This project demonstrates a simple **spam detection system** using the **Multinomial Naive Bayes classifier** from the `scikit-learn` library.  
It classifies email messages as either **Spam** or **Not Spam** based on the text content.

---

## 📌 Project Description

The purpose of this project is to implement a basic machine learning model for **text classification** using **Naive Bayes**.  
The model is trained on a small sample of email messages and predicts whether a given email is spam.

---

## 📊 Dataset

A small dataset with 4 sample email messages:

| Email Text                 | Label      |
|:---------------------------|:------------|
| "Free offer now"            | Spam (1)    |
| "Hi, how are you?"          | Not Spam (0)|
| "Win cash prize"            | Spam (1)    |
| "Let's catch up tomorrow"   | Not Spam (0)|

---

## 📚 Libraries Used

- `scikit-learn`  
- `CountVectorizer` for converting text to numeric features  
- `MultinomialNB` for classification  
- `train_test_split` for splitting data  
- `accuracy_score` for model evaluation  

---

## 📌 Project Workflow

1. **Text Vectorization**
   - Used `CountVectorizer` to convert text messages into a matrix of token counts.

2. **Data Splitting**
   - Split the data into training and testing sets (50-50 split).

3. **Model Training**
   - Trained a `Multinomial Naive Bayes` model on the training data.

4. **Prediction & Evaluation**
   - Predicted labels for the test set and calculated accuracy.

---

## 📦 Installation

Install the required Python libraries using:

```bash
pip install scikit-learn
