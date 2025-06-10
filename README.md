# 🍷 Wine Quality Prediction using Deep Learning

This project builds a deep learning classification model to predict the quality of red wine based on physicochemical attributes using a neural network in TensorFlow/Keras.

## 📊 Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- Dataset: `winequality-red.csv` (contains 12 input features and a quality score label)

## 🚀 Technologies Used
- Python
- TensorFlow / Keras
- Pandas, NumPy, Scikit-learn
- Seaborn, Matplotlib

## 🧠 Model Architecture
- Input layer: 11 features
- Hidden layers: Dense(64), Dense(32)
- Output layer: Softmax activation for multiclass classification

## 📈 Results
- Trained over 50 epochs
- Achieved ~68% validation accuracy

## 📂 How to Run
1. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Run the Jupyter notebook:
    ```bash
    jupyter notebook wine_quality_prediction.ipynb
    ```

## 📌 Visualizations
- Heatmap of feature correlations
- Distribution plots of wine quality
- Box plots and pair plots for exploratory analysis

## ✍️ Author
- Rashmi2001-RS


