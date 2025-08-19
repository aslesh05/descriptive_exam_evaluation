# descriptive_exam_evaluation
Project Overview

This project is an NLP-based system that evaluates descriptive exam answers automatically. It leverages text processing, keyword extraction, similarity measures, and machine learning models to provide a fair and consistent evaluation for student responses.

Features

1.Preprocessing of exam responses (tokenization, stemming, lemmatization).

2.Keyword extraction using RAKE + NLTK.

 3.Grammar and spelling check using language_tool_python.

4. Semantic similarity using scikit-learn and NLP models.

5. Score prediction for descriptive answers.

6. Web-based interface built using Flask.

Project Structure
Descriptive_Exam_Evaluation/
│── Code/
│   │── app.py              # Main Flask app
│   │── tester.py           # Testing script
│   │── templates/          # HTML templates (Flask frontend)
│   │── static/             # (optional) CSS/JS/Images
│
│── Data/                   # Dataset(s) used
│── Models/                 # Saved ML/NLP models
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
│── .gitignore              # Ignored files

🔧 Installation & Setup

Clone the repo

git clone https://github.com/aslesh05/descriptive_exam_evaluation.git
cd descriptive_exam_evaluation


Create a virtual environment (recommended)

python -m venv venv


Activate on Windows

venv\Scripts\activate


Activate on Linux/Mac

source venv/bin/activate


Install dependencies

pip install -r requirements.txt


Run the app

python Code/app.py


Then open in browser → http://127.0.0.1:5000

Tech Stack:

Python 3.x

Flask (for web framework)

NLTK, RAKE-NLTK (for NLP tasks)

Scikit-learn, NumPy, Pandas (for ML + data processing)

LanguageTool (for grammar checks)

Plotly (for visualization)

SQLAlchemy (for database handling)

Future Enhancements:

Improve scoring with transformer-based models (BERT, RoBERTa).

Add support for multiple subjects and exams.

Build a teacher dashboard to review AI-generated scores.

Deploy on Heroku/AWS for real usage.

👨‍💻 Author

Aslesh Ravipati
GitHub: https://github.com/aslesh05
