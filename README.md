


# Calories Burnt Prediction using Machine Learning

## 📌 Project Overview
This project predicts the number of calories burned during physical exercise using machine learning techniques.
The model analyzes user health and activity parameters such as age, gender, height, weight, exercise duration,
heart rate, and body temperature to estimate calories burned.

This project demonstrates end-to-end Data Science workflow including data preprocessing, exploratory data analysis,
model training, hyperparameter tuning, and performance evaluation.

---

## 📊 Dataset
The project uses two datasets:
- `exercise.csv` – Contains user exercise and physiological details
- `calories.csv` – Contains calories burned information

The datasets are merged based on user records for training the model.

---

## ⚙️ Technologies & Tools Used
- Python
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost
- Google Colab

---

## 🧠 Machine Learning Models
- XGBoost Regressor
- Manual Hyperparameter Tuning
- Model selection based on Mean Absolute Error (MAE)

---

## 🔍 Exploratory Data Analysis (EDA)
- Gender distribution analysis
- Age, Height, and Weight distribution plots
- Correlation heatmap
- Missing value analysis
- Feature importance visualization

---

## 📈 Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model was selected based on the lowest MAE.

---

## 🔮 Prediction
The trained model can predict calories burned based on user input:
- Gender
- Age
- Height
- Weight
- Exercise Duration
- Heart Rate
- Body Temperature

---

## 🚀 How to Run the Project
1. Clone the repository
2. Install required libraries
3. Run the Jupyter Notebook (`.ipynb`)
4. Provide user inputs when prompted to get calorie burn prediction

---

## ✅ Results
The XGBoost-based regression model provided accurate predictions with strong performance metrics.
Feature importance analysis shows exercise duration and heart rate as key contributors to calorie burn.


