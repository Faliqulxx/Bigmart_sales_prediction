# 📈 BigMart Sales Prediction

## 📌 Project Description

This project aims to predict **BigMart product sales** using **Machine Learning Regression** techniques based on product characteristics and store information.

The project includes the complete machine learning pipeline, starting from **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, **model training**, **model evaluation**, and **sales prediction**. The objective is to help understand which product and outlet attributes have the greatest impact on sales while providing accurate sales forecasts. The BigMart dataset is widely used as a benchmark for retail sales prediction problems. :contentReference[oaicite:0]{index=0}

---

# 📂 Dataset

## Dataset Source

The dataset used is the **BigMart Sales Dataset**, originally provided as a machine learning regression challenge.

### Dataset Description

The dataset contains product-level and outlet-level information, including:

- Product Identifier
- Product Weight
- Fat Content
- Product Visibility
- Product Type
- Maximum Retail Price (MRP)
- Outlet Identifier
- Outlet Size
- Outlet Type
- Outlet Location Type
- Outlet Establishment Year
- Item Outlet Sales (Target Variable)

---

# 🔍 Exploratory Data Analysis (EDA)

Several analyses were performed before model development, including:

- Missing value analysis
- Data distribution visualization
- Correlation analysis
- Categorical feature exploration
- Outlier detection
- Sales distribution analysis

These analyses help understand the characteristics of the dataset before building predictive models.

---

# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Encoding categorical variables
- Feature scaling
- Feature engineering
- Train-test split

These steps improve model performance and ensure the dataset is suitable for machine learning algorithms.

---

# 🤖 Machine Learning Models

Several regression algorithms were evaluated to identify the best-performing model for sales prediction.

Examples include:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Decision Tree Regressor

The final model was selected based on prediction accuracy using evaluation metrics.

---

# 📊 Model Evaluation

Performance was evaluated using several regression metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The comparison helps determine which model provides the most accurate sales predictions.

---

# 📈 Visualization

The project includes various visualizations such as:

- Sales Distribution
- Correlation Heatmap
- Feature Importance
- Actual vs Predicted Sales
- Model Performance Comparison

These visualizations provide insights into both the dataset and model performance.

---

# 🚀 Features

- Data preprocessing pipeline
- Exploratory Data Analysis (EDA)
- Feature engineering
- Multiple regression model comparison
- Sales prediction
- Model evaluation metrics
- Data visualization

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📁 Project Structure

```
Bigmart_sales_prediction/
│
├── dataset/
│   ├── Train.csv
│   └── Test.csv
│
├── notebook/
│   └── BigMart_Sales_Prediction.ipynb
│
├── models/
│   └── model.pkl
│
├── images/
│
├── requirements.txt
└── README.md
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Faliqulxx/Bigmart_sales_prediction.git
```

Go to the project folder

```bash
cd Bigmart_sales_prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📌 Results

The developed regression model successfully predicts product sales based on product and outlet attributes. Through feature engineering and machine learning, the model provides reliable predictions that can support retail business analysis and decision-making.

---

# 📄 License

This project is intended for educational and research purposes.
