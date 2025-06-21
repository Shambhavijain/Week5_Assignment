# Week5_Assignment
<h2>Overview</h2>
<p>
This project aims to predict house sale prices based on various features using machine learning regression models. The dataset is from Kaggle's House Prices: Advanced Regression Techniques competition.
</p>
<h4>Dataset</h4>
<ul>
  <li>Source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data</li>
  <li>Files used:
    <li>train.csv</li>
    <li>test.csv</li>
  </li>
</ul>
<h4>Project Summary</h4>
<p>
  This project is based on the House Prices: Advanced Regression Techniques Kaggle competition. The goal is to build a machine learning model that can accurately predict the sale prices of residential homes based on various features like lot size, building materials, location, and condition.

We performed the following steps:
<li>Loaded and combined train.csv and test.csv for unified preprocessing.</li>
<li>Handled missing values by dropping highly incomplete columns and imputing others using median (for numerical) and mode (for categorical).</li>
<li>Engineered new features like total square footage (TotalSF), house age, and years since remodeling.</li>
<li>Encoded categorical variables using Label Encoding and One-Hot Encoding.</li>
<li>Trained a Random Forest Regressor model on the cleaned dataset.</li>

This project demonstrates a complete regression pipeline using feature engineering, data preprocessing, and model training to solve a real-world price prediction problem.
</p>
