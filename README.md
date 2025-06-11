# 📧 Email/SMS Spam Classifier 🚫

This project presents a machine learning-based solution to classify email and SMS messages as **Spam** or **Not Spam**. The model analyses text content to predict whether a message is potentially harmful or safe.

## ✨ Features

- **Text Preprocessing**  
  - Lowercasing  
  - Tokenisation  
  - Removal of stopwords and punctuation  
  - Stemming using Porter Stemmer  

- **Vectorisation Approach**  
  Initially, the model was developed using the **Bag of Words (BoW)** technique. However, during the evaluation phase, the **TF-IDF (Term Frequency-Inverse Document Frequency)** method was applied, which significantly improved the model’s performance.

- **Normalisation Attempt**  
  The impact of **MinMax Normalisation** was also tested. However, rather than improving the model’s effectiveness, it slightly reduced the overall accuracy, demonstrating that in this particular text classification problem, normalisation did not contribute positively.

- **Model Exploration**  
  A wide range of models were trained and evaluated, including:  

  - **Logistic Regression**  
  - **Support Vector Classifier (SVC)**  
  - **Decision Tree Classifier**  
  - **K-Nearest Neighbours (KNN)**  
  - **Random Forest Classifier**  
  - **AdaBoost Classifier**  
  - **Bagging Classifier**  
  - **Extra Trees Classifier**  
  - **Gradient Boosting Classifier**  
  - **XGBoost Classifier**  
  - **Voting Classifier**  
  - **Stacking Classifier**  

## 🏆 Best Model

After thorough experimentation, the **Multinomial Naive Bayes** classifier emerged as the best-performing model in terms of accuracy, precision and generalisation capability, particularly well-suited for this text classification task.

## 🚀 Deployment

The model has been deployed using **Streamlit**, offering a simple and interactive web interface:

## App and Dataset link

App - [Email/Spam-Classifier](https://sms-email-spam-classifier-fqgisbq8kjkcpkw4fhedbz.streamlit.app/)
Dataset - [uciml-sms-spam-collection-dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

