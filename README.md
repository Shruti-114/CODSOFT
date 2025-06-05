# 🎬 Movie Rating Prediction

This project predicts movie ratings using features like genre, director, actor, year, and duration from an IMDb India dataset. It applies Linear Regression to estimate ratings.

##  Files
- `IMDb Movies India.csv` – Dataset
- `MovieRatingPrediction.ipynb` – Notebook with full code
- `predicted_movie_ratings.csv` – Model output (actual vs. predicted ratings)

##  Features Used
- Genre
- Director
- Main Actor
- Year (cleaned)
- Duration (cleaned)

##  Tools & Libraries
- Python, Pandas, Scikit-learn, Matplotlib

##  How to Use
1. Open the notebook in Colab
2. Upload the dataset
3. Run all cells to train and test the model
   

# 📊 Sales Prediction Using Advertising Data

## Project Overview
This project builds a **Linear Regression model** to predict product sales based on advertising budget across **TV**, **Radio**, and **Newspaper** media. It includes data exploration, visualizations, and model performance evaluation.

##  Files in This Repository

- `advertising.csv` – Dataset with advertising spends and sales
- `Sales_Predection.ipynb` – Google Colab/Jupyter Notebook with full code
- `processed_advertising.csv` – Cleaned version of the dataset (optional)


##  Tools & Libraries

- **Python**
- `pandas`, `matplotlib`, `seaborn`
- `scikit-learn` for modeling

##  How to Run This Project

###  In Google Colab
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `advertising.csv`
3. Run each cell in `Sales_Predection.ipynb`

# 💳 Credit Card Fraud Detection

## Project Overview
This project applies **Machine Learning** techniques to detect fraudulent credit card transactions. It uses the highly imbalanced `creditcard.csv` dataset, with the goal of accurately classifying transactions as fraudulent or legitimate.


##  Files in This Repository

- `creditcard.csv` – Dataset containing anonymized transaction data
- `creditcardfraud_detection.ipynb` – Jupyter/Colab Notebook with complete data processing and model training
- `processed_creditcard.csv` – Cleaned version of the dataset (optional)

##  Tools & Libraries

- Python
- `pandas`, `numpy`, `seaborn`, `matplotlib`
- `scikit-learn` for modeling
- `StandardScaler` for normalization

##  Dataset Information

- Contains transactions made by European cardholders in September 2013
- 284,807 total transactions
- Only 492 (0.17%) are fraudulent
- Features are anonymized using PCA (`V1` to `V28`), plus `Amount`, `Time`, and `Class`



##  How to Run

###  In Google Colab
1. Upload `creditcard.csv`
2. Run the notebook `credit_fraud_detection.ipynb`

