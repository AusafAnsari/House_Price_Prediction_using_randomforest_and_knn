# 🏠 House Price Prediction using Random Forest and KNN

This project predicts house prices using two machine learning algorithms: **Random Forest** and **K-Nearest Neighbors (KNN)**. It includes model training, predictions, and a GUI for interactive input.

## 📁 Project Structure

```
├── KNN.py                # KNN model training and evaluation
├── house_prices.csv      # Dataset with house features and prices
├── predict.py            # Predicts using trained models
├── predict_knn_gui.py    # GUI for KNN predictions
├── predictions.csv       # Output predictions from models
├── random_forest.py      # Random Forest model training and prediction
```

## 📊 Dataset

- **house_prices.csv** contains features like:
  - Number of rooms
  - Area (in sq ft)
  - Location (optional categorical)
  - Price (target)

You can modify this file to include more relevant data points.

## 🧠 Models

- `KNN.py`: Implements and trains a K-Nearest Neighbors regressor.
- `random_forest.py`: Trains a Random Forest regressor for comparison.

## 🖥 GUI Application

- `predict_knn_gui.py`: A simple Tkinter-based GUI to input house details and get price predictions using the KNN model.

## 🚀 How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AusafAnsari/House_Price_Prediction_using_randomforest_and_knn.git
   cd House_Price_Prediction_using_randomforest_and_knn
   ```

2. **Install Required Libraries**:
   ```bash
   pip install pandas scikit-learn tkinter
   ```

3. **Train and Test Models**:
   ```bash
   python KNN.py
   python random_forest.py
   ```

4. **Run Prediction Script**:
   ```bash
   python predict.py
   ```

5. **Launch GUI**:
   ```bash
   python predict_knn_gui.py
   ```

## 📂 Output

- `predictions.csv` contains the predicted prices after running the models.

## ✅ Future Work

- Add data preprocessing & scaling
- Improve GUI styling
- Add more ML models for comparison (e.g., Linear Regression, XGBoost)
- Create a web-based version using Flask or Streamlit

## 📄 License

This project is licensed under the MIT License. You are free to use and modify it.

---

> Built with ❤️ by [Ausaf Ansari](https://github.com/AusafAnsari)
