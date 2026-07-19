# 📰 Fake News Detection using Machine Learning

## 📌 Project Overview
This project is a Machine Learning-based Fake News Detection System that classifies news articles as **Real** or **Fake**. It uses Natural Language Processing (NLP) techniques to preprocess text data and a machine learning model to make predictions.

## 🎯 Objective
The objective of this project is to identify fake news by analyzing the text of news articles and classifying them into:
- Real News
- Fake News

## 🛠️ Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- NLTK
- TfidfVectorizer

## 📂 Dataset

The dataset used for this project is not included in this repository due to file size limitations.

You can download the Fake News dataset from Kaggle:
https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

After downloading, upload the dataset (`Fake.csv` and `True.csv`) to Google Colab before running the notebook.

These datasets are combined, preprocessed, and used for training and testing the model.

## ⚙️ Project Workflow
1. Import required libraries.
2. Load the datasets.
3. Merge the datasets.
4. Clean and preprocess the text.
5. Convert text into numerical features using TF-IDF Vectorizer.
6. Split the dataset into training and testing sets.
7. Train the Machine Learning model.
8. Evaluate model performance.
9. Predict whether new news is Fake or Real.

## 📊 Machine Learning Algorithm
- Logistic Regression

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

## ▶️ How to Run
1. Open the notebook in Google Colab.
2. Upload the required dataset files.
3. Run all cells.
4. Enter a news article for prediction.
5. The model will classify the news as **Fake** or **Real**.

## 📁 Project Structure

```
Fake-News-Detection/
│── FakeNewsDetection.ipynb
│── Fake.csv
│── True.csv
│── README.md
```

## 📌 Future Improvements
- Deploy using Streamlit or Flask
- Improve accuracy with advanced NLP models
- Add a web interface
- Train on larger datasets

## 👨‍💻 Author
**Name:** Dhruv

**College:** JSS Academy of Technical Education, Noida

**Branch:** Electrical and Electronics Engineering (EEE)

## 📜 License
This project is developed for educational purposes.
