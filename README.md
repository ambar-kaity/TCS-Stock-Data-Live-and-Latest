
# 📈 TCS Stock Data - Live and Latest

A comprehensive machine learning and deep learning project focused on **Tata Consultancy Services (TCS)** stock market data. This project performs **historical data analysis**, **visualization**, **feature engineering**, and **price prediction** using both **Linear Regression** and **LSTM models**.

---

## 🧠 Project Objective

Analyze historical stock data of **TCS** to:
- Understand trading patterns
- Visualize trends and movements
- Engineer meaningful features
- Predict future stock closing prices

---

## 📁 Dataset

- Contains daily trading data (2002 onward)
- Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Dividends`, `Stock Splits`
- [Click here to download the dataset](https://drive.google.com/drive/folders/1SmsFxuLH33lvSXzTLjzcIw0YbxIMdEPu?usp=sharing)

---

## 📌 Technologies Used

| Category | Tools/Languages |
|---------|------------------|
| Programming | Python |
| Libraries | Pandas, Numpy, Matplotlib, Seaborn, scikit-learn, Keras, TensorFlow |
| ML Algorithms | Linear Regression, LSTM (Deep Learning) |
| Dev Environment | Jupyter Notebook, VS Code |

---

## 🔍 Key Features

### ✅ Exploratory Data Analysis (EDA)
- Line plots for stock price trends
- Volume and dividend time-series visualization
- Correlation heatmaps
- Moving averages (30, 50, 200-day)

### ⚙️ Feature Engineering
- Date components: Year, Month, Day, Day of Week
- Lag features (e.g., previous day’s close)
- Moving average crossover strategies
- Daily percentage price change

### 📊 Machine Learning Model
- **Linear Regression**:
  - Input features: Price, Volume, Temporal features
  - Metrics: MSE, R² Score

### 🤖 Deep Learning Model
- **LSTM Neural Network**:
  - Scaled sequential input
  - Batch-wise training using `train_on_batch`
  - Achieved **MAE ≈ 69.5** on test set

### 📈 Model Performance
- Actual vs Predicted price plots
- Prediction CSV export

---

## 🧪 Evaluation Metrics

- **Mean Squared Error (MSE)**
- **R-Squared Score (R²)**
- **Mean Absolute Error (MAE)** for LSTM

---

## 💾 Output

- LSTM predictions stored as `predictions.csv`
- Model optionally saved as `TCS_Stock_Predictor.pkl`

---

## 📬 Contact

For queries or contributions, feel free to open an issue or pull request.
