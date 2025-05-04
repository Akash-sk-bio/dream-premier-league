# 🏏 Dream Premier League (DPL) - AI Team Prediction Project

This project simulates a Dream Premier League (DPL) where users answer cricket-related questions, and based on their answers, a machine learning model predicts their ideal team among Chennai Super Kings (CSK), Royal Challengers Bangalore (RCB), and Mumbai Indians (MI).

## 📋 Objective
To use AI to predict which IPL team a user best fits into based on answers to a cricket-based personality quiz.

## 📁 Dataset
The quiz data is collected manually based on user responses to the following questions:
- What is your cricketing role? (e.g., Batsman, Bowler)
- Favorite batting style or game strategy?
- Preferred playing condition (Home, Away)
- Leadership or team role preferences

## 📊 Features
- Text-based input converted into numerical format using encoding.
- Trained using **Logistic Regression** and **Random Forest** classifiers.
- Predicts the most suitable IPL team.
- Displays model accuracy and prediction result.

## 📌 Technologies Used
- Python 3
- Pandas
- Scikit-learn
- Jupyter Notebook

## 🧰 Project Structure
dream-premier-league/
├── Dream_Premier.ipynb
├── requirements.txt
├── .gitignore
└── README.md


## 🚀 How to Run
```bash
git clone https://github.com/Akash-sk-bio/dream-premier-league.git
cd dream-premier-league
pip install -r requirements.txt
jupyter notebook

✅ Example Output
Predicted Team: Mumbai Indians (MI)
Model Accuracy: 85%

🏆 Future Enhancements
Deploy this as a web app or quiz interface using Streamlit.

Expand the dataset with more user inputs and team labels.

Include more IPL teams and advanced NLP-based answer processing.
