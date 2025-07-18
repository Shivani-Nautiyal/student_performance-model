🧠 Student Performance Prediction System

An end-to-end Machine Learning project to predict a student’s math score based on attributes like gender, parental education, and reading/writing scores.


🚀 Features:

Modular ML pipeline (ingestion → transformation → training)
Data preprocessing using Scikit-learn pipelines
Trains multiple models & auto-selects the best based on R²
Logging & exception handling
Flask web app for prediction
Clean Bootstrap 5 frontend


📂 Project Structure:

├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
├── artifacts/
├── templates/
│   └── home.html
├── app.py
├── requirements.txt
├── setup.py
├── README.md
└── notebook/
    └── data/
        └── stud.csv


📊 Input Features:

Gender
Race/Ethnicity
Parental Level of Education
Lunch Type
Test Preparation Course
Reading Score
Writing Score

🎯 Target Variable: 

Math Score


💡 Tech Stack:

Python 3.8+
Pandas, NumPy, Matplotlib, Scikit-learn
XGBoost, CatBoost, RandomForest
Flask + Bootstrap (Frontend UI)
Git & GitHub (Version control)


🌐 Try the App
🔗 [Click here to try the hosted web app — 
]