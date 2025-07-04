# EDA-On-rainfall
# EDA on Rainfall Prediction

## 🧠 Problem Statement

Predict whether it will rain tomorrow based on weather conditions such as humidity, temperature, wind, and other meteorological features. The goal is to assist in early decision-making for farmers, meteorologists, and planners.

---

## 🧪 Approach

1. **Data Loading & Cleaning**: Loaded weather dataset and handled missing values.
2. **EDA (Exploratory Data Analysis)**: Analyzed distributions, feature relationships, and target variable insights using visualizations.
3. **Feature Engineering**: Encoded categorical features, scaled numerical features.
4. **Modeling**: Used machine learning algorithms for binary classification (RainTomorrow: Yes/No).
5. **Deployment**: Built a Flask web app to take user inputs and predict rainfall.

---

## 📂 Dataset Information

- **File**: `Weather.csv - Dataset.csv`
- **Size**: \~12,000 records
- **Features**:
  - `MinTemp`, `MaxTemp`, `Rainfall`, `WindSpeed9am`, `WindSpeed3pm`, `Humidity9am`, `Humidity3pm`, etc.
  - Target: `RainTomorrow` (Yes/No)

---

## 📊 Exploratory Data Analysis

- Univariate and bivariate analysis
- Correlation heatmaps
- Distribution plots for humidity, temperature, wind
- Missing value treatment

All done in the Jupyter notebook: `new.ipynb`

---

## 🤖 Model Building

- Label Encoding: `encoder.pkl`
- Imputation: `impter.pkl`
- Feature Scaling: `scale.pkl`
- Trained ML Model: `rainfall.pkl`

Model predicts whether it will rain tomorrow based on current input data.

---

## 🌐 Web Application (Flask)

- **Main script**: `app.py`
- **Templates**: `index.html`, `chance.html`, `nochance.html`
- User selects weather inputs, and the app returns a prediction.

---

## 🧭 How to Run This Project

1. Clone the repository or unzip the folder.
2. Install dependencies:

```bash
pip install flask pandas scikit-learn
```

3. Run the Flask app:

```bash
python app.py
```

4. Open browser and go to `http://localhost:5000`

---

## 📸 Screenshots / Output

- `index.html` – Input form for weather data
- `chance.html` – Output page if rain is predicted
- `nochance.html` – Output page if no rain is predicted

---

## ✅ Conclusion

This project demonstrates how real-world weather data can be used to predict rainfall using machine learning, and how the model can be deployed via a simple web interface.

---



