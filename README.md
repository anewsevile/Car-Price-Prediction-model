# 🚗 Car Price Prediction Model

## 📌 Overview

This project builds a **Machine Learning model** to predict the **selling price of used cars** using **Linear Regression**

The workflow includes:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Model Training
* Model Evaluation

---

## 📂 Dataset

The dataset contains information about used cars such as:

* Year
* Present Price
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

**Target Variable:**
`Selling_Price`

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Visualizations

The following charts were created:

* Fuel Type Distribution
* Year vs Selling Price
* Selling Price Histogram
* Correlation Heatmap

---

## 🧠 Model Used

**Linear Regression**

The dataset was split using:

```python
train_test_split(test_size=0.2, random_state=42)
```

---

## 📈 Model Performance

**R² Score:** ~0.19

(This indicates how well the model predicts car prices.)

---

## ▶️ How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Run the notebook:

```bash
jupyter notebook
```

3. Open:

```text
car_price_prediction.ipynb
```

---

## 🚀 Future Improvements

* Try Random Forest Regressor
* Improve feature selection
* Tune model parameters

---

## 👨‍💻 Author

**Your Name**
GitHub: https://github.com/your-username
