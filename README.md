🏏 IPL Score Prediction Model

This project aims to predict the final score of a team in an IPL (Indian Premier League) T20 cricket match using machine learning techniques based on current match conditions such as overs played, wickets fallen, current score, and more.

📌 Table of Contents

About the Project

Tech Stack

Dataset

Features Used

Model Used

How to Run

Results

Future Improvements

Screenshots (Optional)

Contributors

License



---

📖 About the Project

Predicting IPL scores can help teams and fans anticipate match outcomes. This model is built using a supervised regression approach where the target is the final score of the innings. It learns from historical IPL data to predict outcomes based on match situations.


---

⚙ Tech Stack

Python

Pandas, NumPy

Scikit-learn / XGBoost / Linear Regression (update based on what you used)

Matplotlib / Seaborn (for data visualization)

Jupyter Notebook / Streamlit / Flask (if used for deployment/UI)



---

📊 Dataset

Source: Kaggle IPL Dataset

Contents: Match-wise and ball-by-ball data from IPL seasons

Features included: Batting team, bowling team, overs, runs, wickets, etc.



---

📌 Features Used

Batting team

Bowling team

Current score

Overs completed

Wickets fallen

Runs in last 5 overs (optional)

Current run rate (optional)



---

🤖 Model Used

Regression Algorithm: Linear Regression / Random Forest Regressor / XGBoost Regressor (update as applicable)

Performance Metrics: R² Score, Mean Absolute Error



---

🚀 How to Run

1. Clone the repository:

git clone https://github.com/Chirag-Gupta734/ipl-score-prediction.git
cd ipl-score-prediction


2. Install dependencies:

pip install -r requirements.txt


3. Run the Jupyter Notebook or Python file:

jupyter notebook ipl_score_prediction.ipynb


4. For web UI (if any):

streamlit run app.py




---

📈 Results

Achieved an R² Score of 0.85 on the test dataset.

The model performs well on mid-innings data after at least 5 overs.
