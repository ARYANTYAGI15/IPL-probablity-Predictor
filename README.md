# 🏏 IPL Match Win Probability Predictor

This project is a machine learning web app built with **Streamlit** that predicts the **winning probability of an IPL match** in real-time based on live match inputs. It uses **Logistic Regression** as the classification model and follows a clean **data preprocessing pipeline** using `scikit-learn`.

---

## 🚀 Features

- Real-time prediction of winning probabilities for both teams.
- Streamlit web interface for user-friendly interaction.
- Data preprocessing using `ColumnTransformer` and `OneHotEncoder`.
- Logistic Regression for classification.
- Built using a scikit-learn pipeline for modularity and simplicity.

---

## 🔧 Tools & Libraries Used

- `pandas` – data manipulation
- `numpy` – numerical operations
- `scikit-learn` – model, pipeline, preprocessing
- `streamlit` – web app interface

---

## 📊 Inputs to the Model

The app takes the following inputs:

- **Batting Team**
- **Bowling Team**
- **City**
- **Target Score**
- **Current Score**
- **Overs Completed**
- **Wickets Fallen**

The model calculates match context features such as:

- Runs left
- Balls left
- Wickets remaining
- Current run rate
- Required run rate

These are passed through the model to calculate the probability of winning.

---

## 🧠 Model Training

- **Algorithm**: Logistic Regression
- **Handling Categorical Data**: OneHotEncoder
- **Pipeline**: Used to combine preprocessing and model into a single workflow
- **Train-Test Split**: Data split for evaluation using `train_test_split`

---

## 🖥️ How to Run the App

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/ipl-probability-predictor.git
   cd ipl-probability-predictor

### Install Requirement
pip install -r requirements.txt

### Run Streamlit app
streamlit run app.py

🙋‍♂️ Author
Aryan Tyagi
9319152999
📫 Contact: aryan.india1515@gmail.com
