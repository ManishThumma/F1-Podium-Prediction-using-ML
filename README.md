🎯 Problem Statement

Formula 1 race outcomes are driven by a combination of driver skill, team performance, and race conditions. The objective of this project is to:

Predict podium finishes using machine learning

Identify and explain the key factors that influence race success

🗂️ Data Source

Dataset: Formula 1 World Championship (1950–2020)

Source: Kaggle (Rohan Rao)

Scope Used: 2007–2020 (modern era consistency)

The dataset was consolidated from multiple relational tables including races, results, drivers, constructors, and qualifying data.

🛠️ Feature Engineering

Key engineered and selected features include:

Driver Experience: Number of races completed prior to each event

Constructor Strength: Season-level team performance metric

Grid position

Qualifying position

Laps completed

Fastest lap speed

Points scored

These features capture both driver-level and team-level performance dynamics.

🤖 Modeling Approach

Two classification models were trained and evaluated:

Logistic Regression

Random Forest

The data was split into training (70%) and testing (30%) sets.
Models were evaluated using Accuracy, AUC, and Mean Squared Prediction Error (MSPE).

📈 Model Performance

Logistic Regression (Final Model):

Accuracy: 90.3%

AUC: 0.92

MSPE: 0.07

Logistic Regression was selected due to its strong predictive performance and high interpretability. Model coefficients aligned with real-world Formula 1 dynamics, confirming the importance of qualifying position, team strength, and driver experience.

📊 Visualization & Dashboard

An interactive Tableau dashboard was built to visualize and interpret model insights, enabling non-technical users to explore:

Qualifying vs. finishing position relationships

Podium rates by constructor

Driver experience vs. performance

Constructor strength trends over time

The dashboard complements the machine learning model by transforming statistical outputs into intuitive visual patterns.

🧰 Tools & Technologies

Python (Pandas, NumPy, Scikit-Learn)

Logistic Regression, Random Forest

Feature Engineering & Model Evaluation

Tableau (Interactive Dashboards)

🏁 Outcome

This project demonstrates an end-to-end analytics workflow—from raw data integration and feature engineering to predictive modeling and visual storytelling. It showcases how machine learning can be applied to sports analytics while maintaining interpretability and business relevance.

📎 Notes

This project was completed as part of the MS in Business Analytics Capstone at the University of Cincinnati.

Formula 1™ data and logos are used for educational purposes only.
