# 📬 Spam Email Filter using Naive Bayes

This project is a **machine learning-based spam filter** that classifies messages as **spam** or **ham (not spam)** using the **Naive Bayes classifier**. The model was trained on a dataset of labeled messages and achieved an accuracy of **97.77%**.

## 🚀 Features

- Classifies messages as spam or ham
- Uses Multinomial Naive Bayes for classification
- Preprocessing includes text cleaning, tokenization, and vectorization
- Achieved 97.77% accuracy on the test set

## 🛠️ Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK

## 📊 How It Works

1. **Load and clean the data**
2. **Preprocess text**: 
   - Lowercasing  
   - Removing punctuation  
   - Tokenization  
   - Stopword removal  
   - Lemmatization (optional)
3. **Convert text to vectors** using **TF-IDF**
4. **Train a Multinomial Naive Bayes classifier**
5. **Evaluate the model** on test data
