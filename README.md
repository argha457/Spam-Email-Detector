# 📧 Spam Email Detector using Machine Learning

A simple yet effective machine learning app that classifies emails as **Spam** or **Not Spam** using a **Naive Bayes** model. Built with Python, Scikit-learn, Streamlit, and SQLite, this project is perfect for beginners learning **NLP**, **ML**, and **web deployment**.

---

## 🚀 Features

- ✅ Real-time spam classification
- 🧠 Trained Naive Bayes model using `CountVectorizer`
- 🖥️ Interactive Streamlit UI for input and results
- 🗂️ SQLite database for storing classified results
- 🧪 Built using the `spam.csv` dataset
- 📚 Easy to understand and modify for learning

---

## 🧾 Dataset

The app uses a CSV dataset (`spam.csv`) with two columns:
- **Category**: `spam` or `ham` (mapped to 1 or 0)
- **Message**: The email or SMS content

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/spam-email-detector.git
   cd spam-email-detector
   
Install dependencies
bash
pip install streamlit pandas scikit-learn

Run the app
bash
streamlit run model.py
📁 Project Structure
bash
Copy
Edit
📦 Spam-Email-Detector
├── spam.csv                # Labeled dataset
├── spam_detection.db       # SQLite database for storing results
├── model.py                # Main Streamlit + ML script
└── README.md               # Project description
💡 How It Works
Loads the dataset and preprocesses the data.

Converts text to vectors using CountVectorizer.

Trains a Multinomial Naive Bayes classifier.

Uses Streamlit to collect user input and show results.

Saves classified email and result to spam_detection.db.

🧠 Future Improvements
Use TF-IDF for feature extraction

Add model evaluation metrics (accuracy, precision, etc.)

Add result visualization dashboard

Deploy to cloud using Streamlit Sharing or Heroku


🙌 Acknowledgments
Dataset: Collected from public spam email datasets

Libraries used: pandas, scikit-learn, streamlit, sqlite3

✨ Author
Argha Bandyopadhyay
B.Tech CSE, Techno India University
Feel free to connect on LinkedIn
