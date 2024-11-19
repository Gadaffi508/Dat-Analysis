# Laptop Price Prediction with Machine Learning

This project involves predicting laptop prices using a machine learning model based on various laptop features such as RAM, CPU, GPU, and display specifications. The dataset is processed and analyzed in Python, and the results achieve an R² score of **82%** with an RMSE of **1600**.

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [How to Run](#how-to-run)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

---

## Overview
This project aims to provide a price prediction model for laptops based on their specifications. By leveraging machine learning techniques, the model can estimate the price of a laptop with good accuracy.

---

## Dataset
The dataset contains laptop specifications and their corresponding prices. Key features used in the analysis include:
- **RAM** (in GB)
- **CPU Brand, Model, and Speed**
- **GPU Brand, Series, and Model**
- **Display Type and Resolution**
- **Weight and Dimensions**
- **Operating System**

The dataset was cleaned, transformed, and feature-engineered to extract meaningful information.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - `pandas`, `numpy` (Data Cleaning and Manipulation)
  - `matplotlib`, `seaborn` (Visualization)
  - `sklearn` (Machine Learning)
- **Version Control**: Git and GitHub

---

## Project Workflow
1. **Data Cleaning**:
   - Extracted features from raw columns (e.g., CPU, GPU, and Screen Resolution).
   - Converted categorical data to numerical values using mapping.
   - Handled missing values by imputation or assigning default values.

2. **Feature Engineering**:
   - Extracted useful numeric values from text-based features.
   - Created new columns such as `CPU_Series_Numeric`, `GPU_Series_Numeric`, etc.
   - Normalized resolution into `Res_Width` and `Res_Height`.

3. **Model Training**:
   - Used `LinearRegression` for predicting prices.
   - Split the dataset into training and test sets using an 80-20 split.
   - Evaluated the model using R² and RMSE metrics.

4. **Evaluation**:
   - Achieved **R² Score**: 82%
   - **RMSE**: 1600

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/laptop-price-prediction.git
   cd laptop-price-prediction
