# 🦠 COVID-19 Data Analysis Using Python

## 📌 Project Subtitle
**Exploratory Data Analysis and Visualization of Global COVID-19 Trends Using Python**

---

## 📖 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on global COVID-19 data to uncover trends, patterns, and insights across continents.  
The analysis involves **data cleaning, feature engineering, statistical analysis, and data visualization** using Python.

The goal is to transform raw, real-world pandemic data into **meaningful insights** that help understand the impact of COVID-19 in relation to economic and development indicators.

---

## 🎯 Objectives
- Analyze global COVID-19 case and death trends  
- Handle missing values and clean real-world datasets  
- Compare COVID-19 impact across continents  
- Study relationships between GDP, Human Development Index, and COVID-19 outcomes  
- Visualize trends for better interpretability  

---

## 🗂 Dataset Information
- Source: Public global COVID-19 dataset  
- Format: CSV  
- Key Features Used:
  - `continent`
  - `location`
  - `date`
  - `total_cases`
  - `total_deaths`
  - `gdp_per_capita`
  - `human_development_index`

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Key Steps Performed

### 1. Data Understanding
- Checked dataset shape and data types  
- Analyzed unique locations and continents  
- Identified missing values and data distribution  

### 2. Data Cleaning
- Removed duplicate records  
- Dropped rows with missing continent values  
- Filled remaining missing values with zero  
- Converted date column to datetime format  

### 3. Feature Engineering
- Extracted month from date  
- Created death-to-case ratio feature  
- Aggregated data continent-wise  

### 4. Exploratory Data Analysis (EDA)
- Identified continents with:
  - Maximum COVID-19 cases  
  - Minimum GDP per capita  
- Analyzed quartile distribution of total deaths  

### 5. Data Visualization
- Histogram of GDP per capita  
- Scatter plot: Total Cases vs GDP per capita  
- Pairplot for multivariate analysis  
- Bar chart of continent-wise total cases  

### 6. Data Export
- Saved processed and aggregated data into CSV format  

---

## 📊 Key Insights
- COVID-19 impact varies significantly across continents  
- Economic indicators do not always correlate directly with case counts  
- Mortality ratios differ based on development and healthcare factors  

