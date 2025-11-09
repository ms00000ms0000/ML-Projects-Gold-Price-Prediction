# 💰 Gold Price Prediction System — Machine Learning Model  

## 📘 Project Description  
The **Gold Price Prediction System** is a Machine Learning-based project that predicts future gold prices using key financial indicators such as **SPX, GLD, USO, SLV, and EUR/USD**.  
The model is built using the **Random Forest Regressor** algorithm, achieving an impressive **R² score of 0.98**, indicating excellent predictive performance.  

A detailed **Exploratory Data Analysis (EDA)** was conducted to identify correlations, visualize relationships using a **heatmap**, and analyze **GLD price distributions** for trend detection and outlier identification.  
This project highlights the role of **ensemble learning techniques** in financial forecasting and data-driven investment decision-making.  

---

## 🔍 About the Project  
This project demonstrates how **machine learning regression models** can be applied to **financial market analysis** for accurate commodity price forecasting.  
By leveraging multiple economic indicators, the system provides valuable insights into gold price trends, supporting investors and analysts in making informed trading decisions.  

---

## 🧠 Model Architecture  
The project uses a **Random Forest Regressor** with the following specifications:  
* **Algorithm:** Random Forest (Ensemble Learning)  
* **Problem Type:** Regression (Continuous Value Prediction)  
* **Evaluation Metric:** R² Score  

---

## 🧾 Dataset Description  
The dataset consists of historical financial data, including commodity and currency indicators that influence gold prices.  

| Column Name | Description |
| :----------- | :----------------------------------------------------------- |
| `SPX` | S&P 500 Index value |
| `GLD` | SPDR Gold Shares price (target variable) |
| `USO` | United States Oil Fund price |
| `SLV` | iShares Silver Trust price |
| `EUR/USD` | Euro-to-Dollar exchange rate |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical operations  
* **Pandas** – Data preprocessing and analysis  
* **Scikit-learn** – Model training, Random Forest implementation, evaluation  
* **Matplotlib / Seaborn** – Visualization and EDA  

---

## 🚀 Features  
* Predicts gold prices using financial indicators  
* Performs detailed EDA including correlation and trend visualization  
* Utilizes Random Forest for robust, high-accuracy predictions  
* Provides data-driven insights for investment forecasting  
* Achieves an excellent **R² score of 0.98**  

---

## 📊 Results  
The trained **Random Forest Regressor** achieved an **R² score of ~0.98**, effectively predicting gold prices with minimal error and demonstrating exceptional accuracy in market trend forecasting.  

---

## 📁 Repository Structure  

```

📦 ML_Project_Gold_Price_Prediction
│
├── Gold_Price_Prediction.ipynb # Jupyter Notebook with full model code
├── gld_price_data.csv # Dataset used for training and testing
└── README.md # Project documentation
```

---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Gold-Price-Prediction.git
   cd ML-Projects-Gold-Price-Prediction
   ```

2. **Install dependencies:**
  ```bash
  pip install -r requirements.txt
  ```

3. **Run the notebook:**

```bash
jupyter notebook gold_price_prediction.ipynb
```

4. **Execute all cells to train, test, and evaluate the model.**

---

## 📈 Future Improvements

* Integrate live financial data APIs (e.g., Yahoo Finance, Alpha Vantage)

* Use LSTM or GRU models for time-series forecasting

* Deploy a web dashboard using Flask or Streamlit for real-time prediction

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
