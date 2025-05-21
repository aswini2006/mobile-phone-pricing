# 📱 Mobile Phone Price Prediction

This project aims to predict the price range of mobile phones based on their technical specifications using machine learning models. The goal is to help manufacturers or consumers estimate the category (e.g., budget, midrange, premium) a mobile device would fall into.

## 🧾 Dataset

The dataset includes various features such as:
- Battery power
- RAM
- Internal memory
- Camera specs
- Screen dimensions
- 4G/3G/WiFi support
- And more...

### Target Variable
- `price_range`: [0 (Low Cost), 1 (Medium Cost), 2 (High Cost), 3 (Very High Cost)]

## 📊 Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## 🔍 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report

## 🚀 How to Run on Kaggle
1. Upload the dataset (`mobile pricing dataset.csv`) to Kaggle.
2. Make sure the filename is correct in the `pd.read_csv()` function.
3. Run the notebook cells in order.

## 🧪 Example

    ```python
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier()
model.fit(X_train, y_train)
model.score(X_test, y_test)

## 📁 Files
mobile-pricing.ipynb – main Jupyter notebook with all preprocessing and ML code.

mobile pricing dataset.csv – dataset used for training and evaluation.

README.md – project overview and instructions.

requirements.txt – Python dependencies.

## ✅ Requirements
See requirements.txt

## 📄 License
This project is licensed under the MIT License.

