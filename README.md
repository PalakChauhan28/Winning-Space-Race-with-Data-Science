# 🚀 SpaceX Falcon 9 Landing Prediction

## 📌 Overview
This project applies data science and machine learning techniques to predict the success of **SpaceX Falcon 9 first-stage landings**. SpaceX’s reusability strategy significantly reduces launch costs compared to competitors. Accurately forecasting landing outcomes supports both cost estimation and strategic decision-making in the aerospace domain.

## 🎯 Objectives
- Collect Falcon 9 launch data using **SpaceX's public REST API** and **Wikipedia web scraping**.
- Clean, process, and explore the data using **SQL and visual analysis**.
- Develop and compare multiple **classification models** to predict landing success.
- Visualize launch sites and mission outcomes using **interactive mapping tools**.

## 🔧 Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, BeautifulSoup, Matplotlib, Seaborn)
- **SQL (SQLite)** for structured queries
- **Folium** for geospatial mapping
- **Jupyter Notebooks** for development and documentation

## 🔍 Methodology
- **Data Collection**: Acquired structured data using SpaceX API (JSON) and HTML tables from Wikipedia via BeautifulSoup.
- **Data Wrangling**: Cleaned datasets, performed feature extraction, handled missing values, and applied one-hot encoding.
- **Exploratory Data Analysis (EDA)**: Analyzed payloads, orbits, launch sites, and temporal trends using SQL and visual tools.
- **Model Development**:
  - Trained and evaluated Logistic Regression, SVM, Decision Tree, and K-Nearest Neighbors.
  - Used **GridSearchCV** to optimize model performance.
- **Model Evaluation**: Assessed with confusion matrix, accuracy score, and classification reports.

## ✅ Key Findings
- **Success rates** increased from 0% (2010) to ~90% (2019), indicating a strong learning curve.
- **Orbit type** significantly impacts landing outcomes; GEO, SSO, and VLEO showed the highest success rates.
- **Payload mass** varies by orbit; heavier payloads (14,000–16,000 kg) are associated with VLEO missions.
- Final models demonstrate reliable performance in predicting landing success based on launch features.

## 📈 Outcome
This project highlights how machine learning can aid in **mission planning, cost estimation**, and **aerospace strategy**. It serves as a reproducible and modular example of applied data science using real-world, high-impact data.
