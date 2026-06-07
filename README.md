# 🏠 House Price Prediction

## 📌 Project Overview & Task Objective

This notebook aims to predict the sale prices of houses in Ames, Iowa, using machine learning techniques. The primary objective is to build a regression model that accurately estimates house prices based on various features such as area, location, and year built.

## 📂 Dataset Information

The project utilizes a dataset containing detailed information about residential properties in Ames, Iowa. This typically includes `train.csv` and `test.csv` files with features describing aspects of each house, such as `GrLivArea` (above grade living area), `OverallQual` (overall material and finish quality), `GarageCars` (size of garage in car capacity), `TotalBsmtSF` (total basement square feet), and many more. The target variable is `SalePrice`.

**Key Aspects:**
- Over 80 features describing various aspects of residential homes.
- Includes both numerical and categorical features.
- Requires handling of missing values and categorical encoding.

## ✨ Features

- Data loading and initial inspection.
- Handling missing values through imputation or removal.
- Encoding categorical variables (e.g., using LabelEncoder or one-hot encoding).
- Exploratory Data Analysis (EDA) to understand feature distributions and relationships.
- Training and evaluating various regression models (e.g., Linear Regression, Random Forest Regressor).
- Model evaluation using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## 🛠️ Installation

To run this notebook locally, you will need Python installed along with the following libraries. You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 Approach

My approach to house price prediction involved the following steps:

- **Library Import**: Imported essential Python libraries for data manipulation (pandas, numpy), visualization (matplotlib, seaborn), and machine learning (sklearn).
  
- **Data Loading**: Loaded the dataset (e.g., `train.csv`) into a pandas DataFrame.

- **Data Cleaning and Preparation**:
  - Identified and handled missing values across various features.
  - Transformed categorical features into numerical representations suitable for machine learning models.
  - Performed feature engineering where necessary to create more informative variables.
    
- **Exploratory Data Analysis (EDA)**:
  - Analyzed the distribution of `SalePrice` and other key numerical features.
  - Explored relationships between features and the target variable using scatter plots and correlation matrices.
  
- **Model Training and Testing**:
  - Split the dataset into training and testing sets.
  - Trained multiple regression models, such as Linear Regression and Random Forest Regressor.

- **Model Evaluation**: Evaluated the trained models using regression metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE) to assess their predictive performance.

## 🧰 Technologies Used
- P Y T H O N
- P A N D A S
- N U M P Y
- M A T P L O T L I B
- S E A B O R N
- S C I K I T - L E A R N

## 📉 Visualizations
### Living Area vs Sale Price
![image](https://github.com/user-attachments/assets/efd276db-053f-41cb-9b33-23ff62218aee)

**Insights:** The Above Graph Shows that:
- As area increases, sale price increases
- Bigger houses cost more

### Distribution of House Sale Prices
![image](https://github.com/user-attachments/assets/65f72432-fc7c-4f69-9406-fc98d73e284f)

**Insights:** The Above Graph Shows that:
- Most houses are sold for 100,000 to 250,000
- A few expensive houses go above $400,000

### Average Sale Price by Year Built
![image](https://github.com/user-attachments/assets/b5c85a72-fa33-40db-9468-d1e5d2338076)

**Insights:** This graph shows
- how the average house price changes based on the year it was built.
- You’ll notice that houses built in recent years (2000–2010) generally have higher average prices.
- The line may go up and down slightly, but the overall trend is usually upward.

### Average Sale Price by Neighborhood
![image](https://github.com/user-attachments/assets/870996ac-1fa9-415f-9176-b5b3c0df6ebc)

**Insights:** This graph shows
- Some neighborhoods like NridgHt, StoneBr, and NoRidge have much higher average prices
- Others like MeadowV and IDOTRR are more affordable

### Feature Importance from Random Forest
![image](https://github.com/user-attachments/assets/4520dede-f2af-404a-9f8f-5b7a80bf48a7)

**Insights:** This bar graph shows which features the Random Forest model thinks are most useful when predicting house prices. For example, Overall Qual (overall material and finish quality) and Gr Liv Area (above ground living area) are among the most influential. The higher the bar, the more important that feature is in determining the final prediction


## 📊 Results and Insights

### Key Insights:
- Key predictors of house price: Living area, overall quality, and neighborhood.
- Data cleaning and feature analysis improved model accuracy.
- Linear regression gave a good baseline, but
- Random forest had much lower errors and better performance.
- **Random forest** is reliable for real-world house price prediction.

## 🧪 Usage

```bash
# 1. Clone the repository 
git clone https://github.com/Shilpachhatani/House-Price-Prediction.git

# 2. Navigate to the project directory
cd House-Price-Prediction

# 3. Open the notebook
jupyter notebook House_Prirce_Prediction.ipynb

```

## 🤝 Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## 📬 Contact

For questions or collaboration:
- GitHub: `Shilpachhatani`
- Email: shilpachhatani669@gmail.com


