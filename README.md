
# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project is a simple Machine Learning model built using Python to predict house prices based on basic features like area, number of bedrooms, and age of the house.

The goal of this project is to understand the **end-to-end workflow of a basic ML model**, including data handling, training, evaluation, and making predictions.

---

## ⚙️ Technologies Used

* Python
* pandas
* numpy
* scikit-learn

---

## 📂 Dataset

The dataset used is a small CSV file (`house_data.csv`) containing:

| Feature  | Description               |
| -------- | ------------------------- |
| area     | Size of the house (sq ft) |
| bedrooms | Number of bedrooms        |
| age      | Age of the house (years)  |
| price    | House price (target)      |

---

## 🚀 How It Works

1. Load the dataset using pandas
2. Split the data into training and testing sets
3. Train a Linear Regression model
4. Evaluate the model using:

   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)
   * R² Score
5. Take user input and predict house price

---

## 📊 Model Performance

* R² Score: ~0.97
* RMSE: ~8000

> Note: Since the dataset is very small, these values may vary slightly depending on the data split.

---

## ▶️ How to Run

1. Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

2. Place `house_data.csv` in the same folder as the Python file

3. Run the program:

```bash
python your_file_name.py
```

---

## 🧪 Example Input

```
Area: 1300
Bedrooms: 3
Age: 6
```

### Output:

```
Predicted Price: ₹263,787
```

---

## ⚠️ Limitations

* Works only within this range:

  * Area: 800–2000 sq ft
  * Bedrooms: 1–4
  * Age: 1–15 years
* Small dataset (only a few entries)
* Not suitable for real-world pricing

---

## 🎯 Learning Outcomes

* Understanding of basic ML workflow
* Data preprocessing and splitting
* Model training using Linear Regression
* Evaluating model performance
* Taking user input for predictions

---

## 📌 Future Improvements

* Use a larger dataset
* Add more features (location, bathrooms, etc.)
* Try advanced models (Decision Trees, Random Forest)
* Build a GUI or web app

---

## 👨‍💻 Author

Jaswanth Kumar

---

## ⭐ Note

This is a beginner-level project created for learning purposes and does not represent real-world pricing accuracy.
