# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project builds a Machine Learning model to predict house prices using **Linear Regression**.

The objective is to analyze housing features and determine how they influence property prices. The project follows a complete data science workflow including data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── House Price Prediction.ipynb
├── HousePricePrediction.csv
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 📊 Dataset Description

The dataset contains structured housing data with features such as:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Stories
- Parking
- Air Conditioning
- Main Road Access
- Furnishing Status
- Other structural and categorical attributes

### 🎯 Target Variable
- **Price** → House selling price (continuous variable)

---

## 🔎 Exploratory Data Analysis (EDA)

The following steps were performed:

- Checked for missing values
- Analyzed feature distributions
- Performed correlation analysis
- Visualized relationships between price and features

### 📈 Key Observations

- Area shows strong positive correlation with price.
- More bedrooms and bathrooms generally increase property value.
- Some categorical variables required encoding.
- Outliers can influence regression performance.

---

## ⚙️ Data Preprocessing

- Handled categorical variables using encoding techniques
- Performed feature selection
- Split dataset into training and testing sets
- Prepared features for regression modeling

---

## 🤖 Model Used

### Linear Regression

Linear Regression was used to model the relationship between input features and house prices.

### Why Linear Regression?

- Simple and interpretable
- Strong baseline model for regression tasks
- Efficient for structured/tabular data

---

## 📈 Model Evaluation

Model performance was evaluated using:

- **R² Score** → Measures variance explained by the model
- **Mean Squared Error (MSE)** → Measures prediction error magnitude

These metrics help assess model reliability and predictive strength.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Dependencies are listed in `requirements.txt`.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/RakeshChandra2127/House-Price-Prediction.git
cd House-Price-Prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If needed, install manually:

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

### 3️⃣ Run the Notebook

```bash
jupyter notebook
```

Open:

```
House Price Prediction.ipynb
```

Run all cells sequentially.

---

## 🎯 Key Learnings

- Data preprocessing significantly impacts model performance.
- Feature correlation helps identify important predictors.
- Linear Regression works well as a baseline model.
- Proper evaluation metrics are essential for regression tasks.

---

## 🔮 Future Improvements

- Implement Ridge & Lasso Regression
- Perform Cross-Validation
- Apply Feature Engineering techniques
- Try Random Forest / Gradient Boosting
- Deploy the model using Flask or Streamlit

---

## 👤 Author

**Rakesh Chandra Behera**  
Integrated MSc Chemistry  
NIT Rourkela  
Aspiring Data Analyst / Data Scientist  

---

## 📌 License

This project is licensed under the MIT License.
