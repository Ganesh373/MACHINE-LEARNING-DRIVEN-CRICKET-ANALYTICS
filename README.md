# 🏏 Machine Learning Driven Cricket Analytics

A pressure-aware cricket analytics framework that evaluates player performance under high-pressure match situations using ball-by-ball cricket data and Machine Learning.

## 📌 Project Overview

Traditional cricket statistics such as batting average, strike rate, and economy rate often fail to capture how players perform in crucial match situations.

This project introduces a **Pressure Score** and **Clutch Index** framework to identify players who consistently perform under pressure in T20 cricket. The analysis is performed using over 1.5 million ball-by-ball deliveries from IPL and T20 matches (2008–2024). Based on your literature review, the framework models pressure using contextual match variables and evaluates player performance accordingly. :contentReference[oaicite:0]{index=0}

## 🎯 Objectives

- Quantify pressure during cricket matches.
- Evaluate batsmen and bowlers under high-pressure situations.
- Predict dismissal probability using Machine Learning.
- Identify clutch performers.
- Support team selection and tactical decision-making.

## 📊 Dataset

Source: Cricsheet / Kaggle

Coverage:
- IPL and T20 Matches (2008–2024)
- 1.5+ Million Deliveries
- Ball-by-ball match data
- Match-level contextual information

## ⚙️ Features Engineered

### Match Context Features
- Required Run Rate (RRR)
- Current Run Rate (CRR)
- Wickets Remaining
- Balls Remaining
- Match Phase
- Tournament Stage

### Batter Features
- Pressure-Weighted Strike Rate
- Dot Ball Percentage Under Pressure
- Boundary Percentage Under Pressure
- Clutch Contribution Score

### Bowler Features
- Economy Rate Under Pressure
- Dot Ball Rate Under Pressure
- Pressure-Weighted Wicket Rate
- Death Over Effectiveness

## 🧠 Machine Learning Models

- Logistic Regression
- Random Forest

Tasks:
- Dismissal Probability Prediction
- Performance Decline Prediction

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC
- Cross Validation

## 🔬 Methodology

1. Data Preprocessing
2. Pressure Score Calculation
3. Clutch Index Computation
4. Feature Engineering
5. Machine Learning Model Training
6. Player Clustering
7. Association Rule Mining
8. Performance Evaluation

## 🏆 Key Outcomes

- Identified players who perform exceptionally under pressure.
- Distinguished clutch performers from statistical accumulators.
- Generated insights for player selection and match planning.
- Built an interpretable pressure-aware analytics framework.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 👨‍💻 Authors

- Ganesh Datta Ayla
- Vidya R Nayak

Manipal Institute of Technology
