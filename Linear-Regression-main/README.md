# 🏠 Housing Price Prediction using Linear Regression

## 📌 Objective
This project aims to build a **Linear Regression** model that can predict housing prices based on various features like area, number of bedrooms, availability of amenities, and furnishing status.

---

## 📁 Dataset
- Dataset Source: [Kaggle - Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- File Used: `Housing.csv`

---

## 🔧 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📊 Steps Performed

### 1. Import and Preprocess the Dataset
- Loaded the dataset using Pandas
- Performed one-hot encoding for categorical features
- Checked and handled missing values

### 2. Split Data into Train-Test Sets
- Used `train_test_split` from `sklearn.model_selection`

### 3. Fit Linear Regression Model
- Trained the model using `LinearRegression` from `sklearn.linear_model`

### 4. Evaluate Model
- Metrics used:  
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**

### 5. Plot Regression Line & Interpret Coefficients
- Created a regression plot using `'area'` as an example
- Printed and interpreted model coefficients

---

## 📈 Evaluation Results (example output)

- Mean Absolute Error (MAE): 562013.58
- Mean Squared Error (MSE): 6.73e+11
- Root Mean Squared Error (RMSE): 820507.22
- R² Score: 0.6721


---

## 🧠 Interpretation of Coefficients

| Feature               | Interpretation                                              |
|-----------------------|-------------------------------------------------------------|
| `area`                | Every 1 sq ft adds approx ₹750 to price                     |
| `bedrooms`            | Each additional bedroom adds about ₹100,000                |
| `airconditioning_yes` | Having air conditioning increases price by ₹300,000 approx |

---

## ✅ How to Run
1. Clone the repo
2. Make sure `Housing.csv` is in the same directory
3. Run the Jupyter Notebook or Python script

---

## 🤝 Contribution
Feel free to fork, improve, or suggest changes.

---

## 📝 License
This project is open-source and free to use for educational purposes.
