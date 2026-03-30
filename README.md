# 📧 SMS & Email Spam Classifier

**Live Demo:** [Sms/Email_Spam_Classifier](https://sms-email-spam-classifier-szro.onrender.com)

A Machine Learning project that classifies **emails and SMS messages** as **Spam** or **Not Spam (Ham)** using **Naive Bayes**.  

This project includes a **Streamlit web app** for real-time predictions and a **Jupyter Notebook** demonstrating model development, evaluation, and improvement.

---

## 🚀 Features

- Real-time spam/ham prediction through a web interface  
- End-to-end ML workflow from dataset to deployment  
- Clear demonstration of **text preprocessing, vectorization, and model evaluation**

---

## 🛠️ Tech Stack

- **Python**  
- **Scikit-learn** (Naive Bayes, TF-IDF)  
- **Streamlit** (web app)  

---

## 📊 Model Performance

- Algorithm: **Multinomial Naive Bayes**  
- Accuracy: ~**97%** on test dataset  
- Vectorization: **TF-IDF**  

*(Check the Jupyter Notebook for detailed evaluation metrics and confusion matrix)*

---

## 📁 Project Workflow

The project was completed following these steps:

### **1️⃣ Data Cleaning**
- Removed missing values, duplicates, and irrelevant columns  
- Ensured consistent formatting  

### **2️⃣ Exploratory Data Analysis (EDA)**
- Analyzed spam vs ham distribution  
- Visualized frequent words and message lengths  
- Identified patterns in dataset  

### **3️⃣ Text Preprocessing**
- Lowercasing text  
- Removed punctuation, special characters, and numbers  
- Tokenization & stopwords removal  
- Optional: stemming/lemmatization  

### **4️⃣ Model Building**
- Split dataset into training & testing sets  
- Vectorized text using TF-IDF  
- Trained **Naive Bayes classifier**  
- Optional: compared with other models  

### **5️⃣ Model Evaluation**
- Evaluated using **accuracy, precision, recall, F1-score**  
- Generated **confusion matrix**  
- Analyzed performance on spam vs ham messages  

### **6️⃣ Model Improvement**
- Hyperparameter tuning  
- Tried alternative vectorization methods or models  
- Handled class imbalance if present  

### **7️⃣ Convert into Web App**
- Built **Streamlit interface** with input box for user messages  
- Displayed prediction and probability  

### **8️⃣ Deployment**
- Created `requirements.txt` with dependencies  
- Deployed app on **Render** using the following command:  
     streamlit run app.py --server.port 10000 --server.address 0.0.0.0
----  
## 📁 Project Structure

```text
sms_spam_classifier/
│
├─ app.py                # Streamlit app
├─ requirements.txt      # Project dependencies
├─ README.md             # Project description
├─ spam_classifier.ipynb # Jupyter Notebook (model development)
````
-----
- [app.py](https://github.com/diwakar221718/sms-Email_spam_classifier/blob/main/app.py) — Streamlit web app for real-time spam/ham prediction  
- [requirements.txt](https://github.com/diwakar221718/sms-Email_spam_classifier/blob/main/requirements.txt) — Python dependencies for the project  
- [README.md](https://github.com/diwakar221718/sms-Email_spam_classifier/blob/main/README.md) — Project description and instructions  
- [spam_classifier.ipynb](https://github.com/diwakar221718/sms-Email_spam_classifier/blob/main/sms_spam_classifier.ipynb) — Jupyter Notebook with data exploration, preprocessing, model building, and evaluation  
