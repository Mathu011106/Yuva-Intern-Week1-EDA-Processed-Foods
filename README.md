# Yuva Intern Week 1 - Exploratory Data Analysis on Processed Food Products

## 📌 Project Overview

This project is completed as part of the Yuva Intern Week 1 assignment. The project focuses on performing Exploratory Data Analysis (EDA) on an Indian packaged food products dataset.

The analysis explores product categories, nutritional information, calories, sugar, fat, protein, serving size and price to identify useful patterns and relationships in the dataset.

## 🎯 Objectives

- Collect and load a publicly available food processing dataset.
- Understand the structure and characteristics of the dataset.
- Identify and handle missing values.
- Check and clean data types.
- Perform Univariate Analysis.
- Perform Bivariate Analysis.
- Perform Multivariate Analysis.
- Create meaningful data visualizations.
- Identify important patterns and findings from the data.

## 📊 Dataset

The project uses the **Indian Packaged Foods Nutritional Dataset**.

- Number of records: **852**
- Number of features: **25**
- Domain: Packaged Food Products
- Dataset format: CSV

### Important Features

- Product Name
- Brand Name
- Category
- Sub Category
- Serving Size
- Calories
- Carbohydrates
- Proteins
- Total Fat
- Saturated Fat
- Trans Fat
- Sugar
- Sodium
- Dietary Fiber
- Cholesterol
- Calcium
- Iron
- Price

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

- Checked the dataset structure using `info()`.
- Checked missing values.
- Checked duplicate records.
- Converted nutritional columns from text/object format to numeric format.
- Handled missing numeric values using median imputation.
- Prepared the cleaned data for EDA.

## 📈 Exploratory Data Analysis

### 1. Univariate Analysis

The following individual variables were analyzed:

- Product category distribution
- Calories distribution
- Sugar distribution
- Price distribution
- Protein distribution

### 2. Bivariate Analysis

Relationships between two variables were analyzed using:

- Calories vs Total Fat
- Calories vs Protein
- Sugar vs Calories
- Price vs Serving Size

### 3. Multivariate Analysis

Multiple variables were analyzed using:

- Correlation heatmap
- Category-wise nutritional analysis
- Average calories by category

## 🔍 Key Findings

- The dataset contains packaged food products from multiple categories.
- Nutritional values show considerable variation between products.
- Calories have a positive relationship with total fat.
- Calories also show a positive relationship with protein.
- Product prices vary across different serving sizes and product categories.
- Average calorie levels differ between food categories.
- Correlation analysis helps identify relationships among important nutritional variables.

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## 📁 Project Structure

```text
Yuva-Intern-Week1-EDA-Processed-Foods/
│
├── dataset/
│   └── packaged_foods_india.csv
│
├── notebook/
│   └── Yuva_Intern_Week1_EDA.ipynb
│
├── visualizations/
│   ├── univariate/
│   ├── bivariate/
│   └── multivariate/
│
├── screenshots/
│
├── report/
│   └── Yuva_Intern_Week1_EDA_Report.docx
│
└── README.md
