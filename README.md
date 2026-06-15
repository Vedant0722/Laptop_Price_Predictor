# 💻 Laptop Price Predictor

A Machine Learning web application that predicts the price of a laptop based on its specifications. The project uses a trained regression model and an interactive Streamlit interface to provide real-time price predictions.

## 🚀 Demo

Enter laptop specifications such as:

- Brand
- Processor
- RAM
- Storage Type
- Storage Capacity
- GPU
- Operating System
- Screen Size
- Resolution
- Weight

and get an estimated laptop price instantly.

---

## 📌 Problem Statement

Laptop prices vary significantly depending on hardware specifications and brand value. Manually estimating a fair laptop price can be difficult for customers and sellers.

This project leverages Machine Learning to predict laptop prices using historical laptop specification data.

---

## 🛠️ Tech Stack

### Machine Learning
- Python
- Pandas
- NumPy
- Scikit-Learn

### Data Visualization
- Matplotlib
- Seaborn

### Deployment
- Streamlit

### Model
- Random Forest Regressor

---

## 📊 Dataset Features

The model considers various laptop specifications including:

- Company
- Type Name
- RAM
- Weight
- Touchscreen
- IPS Display
- Screen Resolution
- CPU Brand
- HDD
- SSD
- GPU Brand
- Operating System

---

## ⚙️ Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. Streamlit Deployment

---

## 📈 Model Performance

Evaluation Metrics Used:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The Random Forest Regressor achieved strong predictive performance compared to baseline models.

---

## 🖥️ Streamlit Interface

The web application provides:

✅ User-friendly UI

✅ Real-time price prediction

✅ Interactive input selection

✅ Fast inference using a trained model

---

## 📂 Project Structure

```
Laptop_Price_Predictor/
│
├── app.py
├── prediction_pipeline.pkl
├── df.pkl
├── notebooks/
│   └── Laptop_Price_Prediction.ipynb
│
├── images/
│   └── app_screenshot.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Laptop_Price_Predictor.git
```

Move into the project directory:

```bash
cd Laptop_Price_Predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 🎯 Future Improvements

- Deep Learning based price prediction
- Real-time laptop market data integration
- Cloud deployment
- Explainable AI (SHAP)
- Recommendation system for similar laptops

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Preprocessing
- Feature Engineering
- Regression Models
- Model Evaluation
- Streamlit Deployment
- End-to-End Machine Learning Pipelines

---

## 👨‍💻 Author

Vedant Saikhede

Aspiring Machine Learning & Generative AI Engineer
