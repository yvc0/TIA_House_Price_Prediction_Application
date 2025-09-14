# 🏠 Hyderabad House Price Prediction App

This is a **Streamlit-based machine learning application** that predicts **house prices in Hyderabad** based on synthetic real-estate data.  
The app uses features like area, bedrooms, bathrooms, and location to estimate the price of a house.

---

## 🚀 Features
- Interactive **web interface** built with Streamlit.
- Synthetic dataset with **Hyderabad localities**:
  - Madhapur
  - Kukatpally
  - Kondapur
  - Gachibowli
  - Miyapur
- Machine Learning model pipeline with:
  - **OneHotEncoding** for categorical features (Location)
  - **Linear Regression** for prediction
- Displays **model performance metrics** (MAE, R² Score) in the sidebar.
- Instant prediction based on user input.

---

## 📂 Project Structure
```
hyderabad-house-price-app/
├── house_price_app.py   # Main Streamlit application
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

---

## 📦 Installation

1. **Clone this repository** (or copy project files):
   ```bash
   git clone https://github.com/your-username/hyderabad-house-price-app.git
   cd hyderabad-house-price-app
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Run the Application
Run the Streamlit app with:
```bash
streamlit run house_price_app.py
```

The app will open in your browser at:
```
http://localhost:8501
```

---

## 📊 Example Prediction
- Area: **2000 sqft**
- Bedrooms: **3**
- Bathrooms: **2**
- Location: **Gachibowli**

👉 The app may predict an estimated price of **₹ 1.8 Cr** (example output).

---

## 🛠 Requirements
Contents of `requirements.txt`:
```
streamlit
pandas
numpy
scikit-learn
```

---

## 💡 Future Improvements
- Use a **real Hyderabad housing dataset** instead of synthetic data.
- Try advanced ML models (Random Forest, XGBoost).
- Add **data visualization** for price trends by locality.
- Deploy app on **Streamlit Cloud or Heroku**.

---

## 📌 Disclaimer
⚠️ This project uses **synthetic data** and is meant for **educational/demo purposes only**.  
It does not represent real Hyderabad housing market prices.
