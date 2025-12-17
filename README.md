# 🚢 Titanic Dataset – Exploratory Data Analysis (EDA)
## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python.
The goal is to analyze passenger data and extract meaningful insights using statistical methods and visual exploration to understand factors that influenced survival.

## 🎯 Objective

- Understand the structure and quality of the dataset

- Explore relationships between different features

- Identify patterns and trends affecting passenger survival

- Visualize insights using plots and charts

## 🛠 Tools & Technologies Used

- Python

- Pandas – Data manipulation and analysis

- Matplotlib – Data visualization

- Seaborn – Statistical data visualization

- Jupyter Notebook – Interactive analysis

## 📂 Dataset

- Dataset Name: Titanic Dataset

- Source: Kaggle 

- Description: Contains passenger details such as age, gender, class, fare, and survival status.

## 📁 Project Structure
Titanic-EDA/

│

├── titanic.csv                # Dataset

├── Titanic_EDA.ipynb          # Jupyter Notebook with EDA

├── Titanic_EDA_Report.pdf     # PDF report of findings

├── README.md                  # Project documentation

## 🔍 Exploratory Data Analysis Steps
### 1. Data Loading & Inspection

- Used .head(), .info(), .shape() to understand data structure

- Checked missing values using .isnull().sum()

### 2. Statistical Summary

- Used .describe() to analyze numerical features

- Used .value_counts() for categorical features

### 3. Univariate Analysis

- Survival distribution

- Gender distribution

- Age and fare distribution

### 4. Bivariate Analysis

- Survival vs Gender

- Survival vs Passenger Class

- Fare vs Survival

### 5. Multivariate Analysis

- Pairplots to study feature interactions

- Correlation heatmap to identify relationships

## 📊 Key Insights

- Females had a significantly higher survival rate than males

- First-class passengers had better survival chances

- Passengers who paid higher fares were more likely to survive

- Younger passengers and children had higher survival rates

- Socio-economic factors played a major role in survival

## 📈 Visualizations Used

- Count plots

- Histograms

- Box plots

- Scatter plots

- Pair plots

- Heatmaps

## 📄 Deliverables

✅ Jupyter Notebook with code, visuals, and observations

✅ PDF Report summarizing findings

✅ GitHub Repository with complete documentation
