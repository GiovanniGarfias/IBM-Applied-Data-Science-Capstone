 DATA SCIENCE CAPSTONE IBM COURSERA 
 Project Overview

This project analyzes SpaceX Falcon 9 launch data to understand the key factors that influence first-stage landing success. Using historical launch records, interactive visualizations, and machine learning models, the project aims to predict whether a Falcon 9 booster will successfully land after launch.

- Objectives

Analyze historical SpaceX launch data

Identify key factors influencing landing success

Build interactive dashboards and geospatial visualizations

Develop and evaluate machine learning classification models to predict launch outcomes

- Project Structure

Data Collection: SpaceX API and web scraping

Data Wrangling & EDA: Cleaning, transformation, and exploratory analysis

Visualization: Interactive charts (Plotly Dash) and maps (Folium)

Predictive Modeling: Logistic Regression, SVM, Decision Tree, and KNN

Evaluation: Accuracy, F1-score, and confusion matrix analysis

- Tools & Technologies

Python (Pandas, NumPy, Scikit-learn)

SQL (SQLite)

Plotly Dash

Folium

Matplotlib & Seaborn

Jupyter Notebooks

- Key Results

Launch success rates improved over time with newer Falcon 9 booster versions

Launch site, payload mass, and booster technology significantly affect mission outcomes

Multiple classification models achieved similar performance (~83% accuracy)

Logistic Regression was selected as the final model due to its simplicity and interpretability

- Repository Contents

notebooks/ – Data analysis and machine learning notebooks

dashboard/ – Interactive Plotly Dash application

data/ – Datasets used in the project

presentation/ – Final capstone presentation (PDF & PPTX)

- How to Run the Dashboard
cd dashboard
python spacex_dash_app.py


Then open your browser at:

http://127.0.0.1:8050/
