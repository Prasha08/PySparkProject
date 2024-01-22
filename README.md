# Fake News Detection - A PySpark and Apache Spark Project

***Overview:***
This project focuses on building a Fake News Detection system using Apache Spark and PySpark. The goal is to create a robust pipeline that preprocesses textual data, extracts features, and trains machine learning models to classify news articles as either fake or legitimate.

***Key Features:***
- Data Preprocessing: Utilizes PySpark for data cleaning, handling missing values, and removing special characters from the text, title, and author columns.
- Exploratory Data Analysis (EDA): Visualizes data distribution, word lengths, and top authors using Seaborn and Matplotlib.
- Feature Engineering: Tokenizes, removes stopwords, and applies TF-IDF to text, title, and author columns to create feature vectors.
- Model Training: Employs three different classification models (Logistic Regression, Decision Tree, SVM) to predict fake news based on the engineered features.
- Model Evaluation: Utilizes ROC curves, AUC scores, and confusion matrices to assess the performance of each model.
- Cross-Validation: Implements cross-validation to fine-tune hyperparameters and select the best-performing model.
- Tableau Dashboard: Developed an interactive Tableau Dashboard to visually represent key insights and model comparisons.

***Dependencies:***
- Apache Spark
- PySpark
- Seaborn
- Matplotlib
- Scikit-learn
