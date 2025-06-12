### 📘 Project Overview

This dissertation explores how integrating sentiment analysis of financial news and social media can enhance the predictive performance of technical indicator-based stock price movement models. An XGBoost classifier is developed to forecast short-term price movements, using both traditional technical indicators and sentiment scores generated via FinBERT.

### 🔍 Key Features

* **Sentiment Analysis:** Used FinBERT to classify and vectorize financial news and tweets related to selected stocks.
* **Technical Indicators:** Calculated popular indicators such as RSI, MACD, SMA, and Bollinger Bands from historical price data.
* **Modeling:** Built an XGBoost model to classify stock movement directions (up/down), optimizing using hyperparameter tuning and evaluating with accuracy, F1-score, and AUC-ROC.
* **Explainability:** Applied SHAP values (Beeswarm, Force Plot, Feature Importance) to interpret and explain model decisions.

### 🛠️ Tools and Libraries

* Python (Pandas, Scikit-learn, XGBoost, SHAP, FinBERT, Matplotlib, Seaborn)
* Jupyter Notebook

### 🏆 Result

* Achieved **84/100** (Distinction).
* Demonstrated that sentiment data improves model performance over using technical indicators alone.
