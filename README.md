# 🏅 Olympics Data Analysis

This project is a comprehensive data analysis of Olympic athletes and sports using Python. It investigates historical data to discover trends and build ML model to classify athlete outcome.

## 📊 Project Overview

Using **Pandas**, **Matplotlib**, **Seaborn**, and **Scikit-learn** :
- Data cleaning and feature engineering
- EDA (Exploratory Data Analysis)
- Classification modeling ( Random Forest)
- Model evaluation using key metrics

## 📁 Dataset

Data-
- athlete_events.csv
- noc_regions.csv

The dataset includes:
- Athlete demographics: name, age, gender
- Olympic details: team, sport, event, medal, year, country (NOC), city, season

Dataset Source: [Kaggle - 120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)


## 📈 Insights

- Countries with most medals
- Sport-wise medal dominance
- Gender participation trends over time
- Age distribution among athletes
- Athletes with most Medals and appearances over the years.
- Medal trends by season, gender and year
- Events with highest number of participants


## 🧠 Machine Learning Modeling

This project uses a **Random Forest Classifier** to predict:
- Whether an athlete won a medal based on features like age, sex, sport, country, season, year, and event


Modeling Steps:
- `train_test_split` for data partitioning
- `RandomForestClassifier` for training
- Evaluation via:
  - Accuracy score
  - Classification report
  - Confusion matrix
  - Feature Importance


## 🛠️ Technologies Used

- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
