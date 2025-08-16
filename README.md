🐧 Penguin Sex Determination using Machine Learning
📌 Overview

This project applies machine learning techniques to predict the sex of penguins using the Palmer Penguins dataset. Traditional methods (like DNA testing) are invasive, costly, and time-consuming. Our goal is to provide a non-invasive, data-driven solution by leveraging physical measurements such as:

Culmen Length (mm)

Culmen Depth (mm)

Flipper Length (mm)

Body Mass (g)

The project compares multiple ML models and highlights the best-performing approach for ecological research and conservation studies.

📊 Dataset

Source: Palmer Penguins Dataset

Species: Adélie, Chinstrap, Gentoo

Features Used:

culmen_length_mm

culmen_depth_mm

flipper_length_mm

body_mass_g

Target Variable: Sex (Male / Female)

⚙️ Methodology

Data Preprocessing

Handled missing values

Encoded target labels (Male → 0, Female → 1)

Normalized features using StandardScaler

Train/test split (80/20)

Models Implemented

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

Evaluation Metrics

Accuracy

Confusion Matrix

Precision, Recall, F1-Score

Feature Importance (Random Forest)

🚀 Results

Random Forest → ⭐ Best model (~96% accuracy)

SVM → ~92% accuracy

Logistic Regression → ~90% accuracy

🔑 Key Insight: Flipper length and body mass were the most important predictors.

📂 Project Structure
├── data/
│   └── penguins.csv
├── notebooks/
│   └── penguin_sex_classification.ipynb
├── src/
│   └── model_training.py
├── results/
│   └── feature_importance.png
├── README.md
└── requirements.txt

🛠️ Tech Stack

Language: Python

Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

🔮 Future Enhancements

Develop species-specific models for better accuracy

Add environmental & behavioral features

Experiment with advanced algorithms (XGBoost, Neural Networks, AutoML)

Deploy as a mobile/web application for real-time field usage

Build an interactive dashboard for visualization

📜 License

This project is licensed under the MIT License.
