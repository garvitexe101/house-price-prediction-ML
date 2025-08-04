# house-price-prediction-ML

# 🏡 **House Price Prediction using Regression Models**

A machine learning model built to predict real estate prices using key house features. Trained on structured housing data, this project demonstrates how regression can be applied to real-world business problems.

---

## 🚀 **Project Purpose**

> Predict house prices using important numerical and categorical features such as square footage, number of bedrooms, bathrooms, condition, and construction year.

---

## ⚙️ **Model Functioning — How It Works**

🔍 **1. Data Collection & Cleaning**  
- Raw data from `train.csv` and `test.csv` loaded.
- Missing values handled, outliers removed, and formatting adjusted.

📊 **2. Exploratory Data Analysis (EDA)**  
- Visualized distributions (`distribution_plots.png`, `scatter_plots.png`)
- Observed relationships between features and target (`SalePrice`).

🧠 **3. Feature Selection**  
- Selected top predictors:  
  `GrLivArea`, `GarageArea`, `YearBuilt`, `OverallQual`, `TotalBsmtSF`, `BedroomAbvGr`, `Bathroom`, `Condition`

🧮 **4. Model Training: Linear Regression**  
- Applied Linear Regression on selected features
- Trained using `train.csv`, validated using `test.csv`

📈 **5. Prediction & Evaluation**  
- Predictions visualized with `actual_vs_predicted.png`
- Evaluated using R² score (closer to 1 means better fit)

---

## 🎯 **Key Use Cases**

✅ **Real Estate Agencies**  
> Automate pricing for property listings to stay competitive.

✅ **Home Buyers/Sellers**  
> Get a fair market estimate based on property features.

✅ **Banks & Mortgage Lenders**  
> Use price prediction for credit risk assessment and lending limits.

✅ **Government Agencies**  
> Predict property tax values and urban planning decisions.

✅ **Data Science & ML Students**  
> Learn regression modeling using a practical example.

---

## 💻 **Tech Stack**

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-Learn (LinearRegression)**  
- **Jupyter Notebook**

---

## 🧾 **Features Analyzed**

- 📌 Bedrooms (`BedroomAbvGr`)
- 📌 Bathrooms (`Bathroom`)
- 📌 Area (`GrLivArea`, `GarageArea`, `TotalBsmtSF`, `1stFlrSF`)
- 📌 Condition & Quality (`OverallQual`, `OverallCond`)
- 📌 Built Year (`YearBuilt`)
- 📌 Fireplaces

---

## 🖼️ **Visual Output Highlights**

| Visual | Description |
|--------|-------------|
| `actual_vs_predicted.png` | 📍 Compares true vs predicted house prices |
| `distribution_plots.png` | 📍 Distribution of price, area, garage, year built |
| `additional_distribution_plots.png` | 📍 Fireplace and quality distribution |
| `scatter_plots.png` | 📍 Shows how each feature relates to price |

---

## 📦 **Run Locally**

```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
jupyter notebook main.ipynb
