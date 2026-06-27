# 🌊 Flood Prediction Using Machine Learning

## 📌 Project Overview

Floods are one of the most devastating natural disasters, causing significant damage to life and property. This project develops an **Early Flood Prediction System** using Machine Learning algorithms to predict flood occurrences based on rainfall data.

The project analyzes historical rainfall patterns, performs data preprocessing, exploratory data analysis (EDA), trains multiple machine learning models, compares their performance, and deploys the best model using a Flask web application.

---

## 🎯 Objectives

- Analyze rainfall data.
- Perform Exploratory Data Analysis (EDA).
- Build multiple machine learning models.
- Compare model performance.
- Select the best-performing model.
- Save the trained model.
- Deploy the model using Flask.

---

## 📂 Dataset

The dataset contains historical rainfall information including:

- YEAR
- JAN
- FEB
- MAR
- APR
- MAY
- JUN
- JUL
- AUG
- SEP
- OCT
- NOV
- DEC
- Jan-Feb
- Mar-May
- Jun-Sep
- Oct-Dec
- ANNUAL
- FLOODS (Target Variable)

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Flask
- Joblib
- Pickle

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset information
- Missing value analysis
- Monthly rainfall visualization
- Annual rainfall distribution
- Flood class distribution
- Correlation heatmap
- Scatter plots
- Violin plots
- Box plots
- Feature importance analysis

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

Evaluation Metrics:

- Accuracy
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- ROC Curve

---

## 🏆 Best Model

After comparison, **XGBoost Classifier** achieved the highest prediction performance and was selected as the final model.

The trained model is saved using:

- Joblib
- Pickle

Generated files:

- flood_xgb_model.pkl
- scaler.pkl
- flood_model_pickle.pkl

---

## 🌐 Flask Web Application

The project includes a Flask application for real-time flood prediction.

### Features

- User-friendly interface
- Accepts rainfall data
- Predicts flood occurrence
- Displays prediction confidence

Run the application:

```bash
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

## 📁 Project Structure

```
Flood-Prediction/
│
├── flood_data.csv
├── flood_prediction.ipynb
├── app.py
├── flood_xgb_model.pkl
├── scaler.pkl
├── flood_model_pickle.pkl
├── templates/
│   └── index.html
├── static/
├── README.md
└── requirements.txt
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Flood-Prediction.git
```

Move into the project folder

```bash
cd Flood-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python app.py
```

---

## 📈 Results

- Data preprocessing completed successfully.
- Multiple machine learning algorithms were trained.
- XGBoost outperformed other models.
- The application predicts flood risk with high accuracy.
- Model deployment completed using Flask.

---

## 🔮 Future Improvements

- Integrate real-time weather APIs.
- Predict flood severity levels.
- Add GIS map visualization.
- SMS and Email alert system.
- Deploy on cloud platforms such as AWS, Azure, or Render.

---

## 👩‍💻 Author

**Kaveri**

Electronics and Communication Engineering Student

Machine Learning & AI Enthusiast

---

## 📜 License

This project is developed for educational and research purposes.
