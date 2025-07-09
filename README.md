# 🚗 Car Price Prediction Web App

A machine learning-powered web application that predicts the resale price of used cars based on input features like brand, model, year, kilometers driven, and fuel type. Built with **Flask**, **Pandas**, and **Scikit-learn**.

---

---

## ⚙️ Tech Stack

- **Frontend**: HTML (via Flask's Jinja2 templates)
- **Backend**: Python, Flask
- **ML Model**: Scikit-learn (Linear Regression)
- **Libraries**: Pandas, NumPy

---

## 🧠 Machine Learning Overview

- **Algorithm Used**: Linear Regression
- **Features**:
  - `company`
  - `name` (model)
  - `year`
  - `fuel_type`
  - `kms_driven`
- **Target Variable**: Selling price
- The model is trained using `Cleaned_Car_data.csv` and saved as `LinearRegressionModel.pkl`.

---

## 🚀 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction

python application.py
