<h1 align="center">📩 SMS Spam Classifier 🚀</h1>

<p align="center">
  A Machine Learning Web Application that classifies SMS messages as <b>Spam</b> or <b>Not Spam</b> using Natural Language Processing.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/NLP-NLTK-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Deployment-Streamlit-red?style=for-the-badge&logo=streamlit">
</p>

## 🔗 Live Demo

👉 https://nlp-textshield-classifier.streamlit.app/


## 📖 Project Overview

Spam messages are a major issue in digital communication.  
This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically detect whether a message is Spam or Ham (Not Spam).

The model is trained on SMS data and deployed as an interactive web application using **Streamlit Cloud**.


## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- NLTK  
- Pandas  
- NumPy  
- Streamlit  
- Pickle (Model Serialization)  
- Git & GitHub  


## ⚙️ Machine Learning Workflow

1. Data Cleaning  
2. Text Preprocessing  
   - Lowercasing  
   - Tokenization  
   - Stopword Removal  
   - Punctuation Removal  
   - Stemming  
3. Feature Extraction using TF-IDF  
4. Model Training (Multinomial Naive Bayes)  
5. Model Evaluation  
6. Deployment using Streamlit Cloud  


## 📊 Model Performance

- ✅ Accuracy: ~97%
- ✅ High precision in spam detection
- ✅ Fast prediction time



## 🖥️ Application Features

✔ Real-time SMS spam prediction  
✔ Clean and user-friendly interface  
✔ Lightweight and fast  
✔ Cloud deployed  
✔ Handles dynamic user input  


## 📂 Project Structure
```
smsspamclassifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
```

## 🚀 Run Locally

1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/smsspamclassifier.git
cd smsspamclassifier

pip install -r requirements.txt

streamlit run app.py



# 📌 Important

After `streamlit run app.py`:

- Your terminal will show:
  
Local URL: http://localhost:8501



- Open that link in your browser.
- Your app will run locally.



## 📌 Example Spam Message

Congratulations! You have won a $1000 gift card. Click here to claim now!


## 🎯 Future Improvements

- Add deep learning model
- Improve UI styling
- Add API version

---

## 👩‍💻 Author

**Janaki Sravanthi Paluchuri**
