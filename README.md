
# 📈 Next-Day Stock Trend Predictor

This project builds a machine learning model to predict whether a stock's next-day trend will be **Bullish**, **Bearish**, or **Stable**, using historical trading data from AAPL (Apple Inc.).

## 🧠 Model

- Algorithm: Random Forest Classifier
- Features used:
  - `close`: Closing price
  - `volume`: Daily trading volume
- Target:
  - `Bullish`: Next-day price increase > 1%
  - `Bearish`: Next-day price decrease < -1%
  - `Stable`: Price change within ±1%

## 📊 App Features (via Streamlit)

- 📥 Input today's features manually or via `.csv` upload
- 🤖 Model predicts next-day stock trend
- 📌 Visualizes feature importance
- 🔍 Clean UI and simple deployment

## 📁 Project Structure

```
stock-trend-app/
├── app.py                     # Streamlit app source
├── model/
│   └── rf_model.pkl           # Trained Random Forest model
├── data/
│   └── sample_input.csv       # Example input format
└── README.md
```

## ▶️ How to Run

1. Install dependencies:
```bash
pip install streamlit pandas scikit-learn joblib matplotlib
```

2. Run the app:
```bash
streamlit run app.py
```

## 🚀 Deployment Ideas
You can deploy using:
- [Streamlit Cloud](https://streamlit.io)
- [Render](https://render.com)
- [HuggingFace Spaces](https://huggingface.co/spaces)

## 👤 Author

**Jianyi Wu**  
Machine Learning & Data Science in Economics, WUSTL  
[GitHub Profile](https://github.com/JennyWu0630)
