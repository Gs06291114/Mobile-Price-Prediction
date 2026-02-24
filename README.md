# 📱 Mobile Price Prediction using Machine Learning

This project predicts the price of a smartphone based on its specifications using Machine Learning.

---

## 🚀 Project Overview

The model takes various smartphone features such as brand, RAM, battery capacity, camera specifications, and clock speed, and predicts the expected price.

A user-friendly web interface is built using Gradio.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Gradio
- Pickle

---

## 📊 Features Used for Prediction

- Brand
- Screen Size (inches)
- Front Camera (MP)
- Back Camera (MP)
- Battery (mAh)
- RAM (GB)
- ROM (GB)
- Clock Speed (GHz)

---

## 🤖 Machine Learning Model

- Linear Regression
- Pipeline with ColumnTransformer
- StandardScaler for numerical features
- OneHotEncoder for categorical features
- Train-Test Split (80-20)

---

## 📈 Model Performance

The model is trained using an 80-20 train-test split and evaluated using regression metrics.

---

## 💻 How to Run This Project

1. Clone the repository:
   git clone https://github.com/yourusername/repository-name.git

2. Install required libraries:
   pip install -r requirements.txt

3. Run the Jupyter Notebook:
   mobile_price_prediction.ipynb

4. Launch the Gradio interface to predict prices.

---

## 📦 Project Structure

mobile_price_prediction/
│
├── mobile_price_prediction.ipynb
├── smartphones_dataset.csv
├── mobile_price_model.pkl
├── requirements.txt
└── README.md

---

## 🎯 Future Improvements

- Add model evaluation metrics (R2 score, MAE, RMSE)
- Deploy as a web application
- Improve feature engineering
- Try advanced models like Random Forest or XGBoost

---

## 👨‍💻 Author

Govind Sharma  
Bachelor of Computer Engineering  
Ahmedabad Institute of Technology  