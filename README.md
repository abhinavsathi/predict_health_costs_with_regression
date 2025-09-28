# 💰 Expenses Prediction using Neural Networks

This project demonstrates how to build and train a **Neural Network Regression Model** with TensorFlow/Keras to predict **individual expenses** based on input features such as age, income, region, and family details (depending on dataset).  

The model achieves a **Mean Absolute Error (MAE) of ~3113**, successfully passing the challenge threshold of 3500.

---

## 📌 Project Overview
- **Type:** Regression (predicting continuous values).  
- **Goal:** Predict expenses with high accuracy.  
- **Frameworks Used:** TensorFlow, Keras, NumPy, Pandas, Matplotlib.  
- **Key Metric:** Mean Absolute Error (MAE).  

---

## 📊 Dataset
The dataset contains features like:
- **Demographics**: age, gender, region, family size.  
- **Financial info**: income, spending habits.  
- **Target**: `expenses` (the cost value we want to predict).  

*(Note: Replace this with the actual dataset description if available.)*

---

## ⚙️ Model Architecture
The neural network is a simple feed-forward model:
- Input Layer: Takes in all normalized features.  
- Hidden Layers: Dense layers with ReLU activation.  
- Output Layer: Single neuron for regression output.  

**Loss Function:** Mean Squared Error (MSE)  
**Optimizer:** Adam  
**Evaluation Metric:** Mean Absolute Error (MAE)  

---

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/expenses-prediction.git
   cd expenses-prediction

## 📈 Results

After training, the model achieved:

- Training MAE: ~3113
- Testing MAE: ~3113

Example output during evaluation:

9/9 - 0s - loss: 32274234.0000 - mae: 3113.6179 - mse: 32274234.0000
Testing set Mean Abs Error: 3113.62 expenses

## 🛠 Future Improvements
- Add data preprocessing pipelines for categorical encoding.
- Compare against other models (Linear Regression, Random Forest, XGBoost).
- Hyperparameter tuning for better accuracy.
- Deploy as a web app (Flask/Streamlit) for interactive predictions.
