# 📩 SMS Spam Classifier

This project is a machine learning-based solution to classify SMS messages as either **spam** or **ham** (non-spam).  
It uses Natural Language Processing (NLP) techniques like TF-IDF for feature extraction and traditional machine learning algorithms for classification.

---

## 🧠 What It Does

- Loads and processes the SMS Spam Collection dataset
- Cleans and prepares text data for analysis
- Converts text into numerical features using **TF-IDF Vectorization**
- Trains models including:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
- Evaluates models using accuracy, confusion matrix, and classification report

---

## 🔧 Technologies Used

- **Programming Language**: Python  
- **Libraries**:
  - `pandas`, `numpy` for data handling
  - `sklearn` for model building and evaluation
  - `matplotlib`, `seaborn` for visualizations

---

## 📊 Model Performance

| Model                | Accuracy |
|---------------------|----------|
| Naive Bayes         | ~98%     |
| Logistic Regression | ~97%     |
| SVM (Linear)        | ~98%     |

---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Upload your `kaggle.json` to download the dataset  
3. Execute each cell step-by-step to preprocess, train, and evaluate the models  
4. Try out your own SMS samples for prediction

---

## ✍️ Author

**Divya Ramnani**  
B.Tech CSE (Data Science)  
Aspiring Data Scientist | Passionate about Machine Learning & AI
