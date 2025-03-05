# EDA Portfolio Project - Treadmill Buyer Profile

## Project Overview
The market research team at **AeroFit** aims to identify key customer characteristics for each treadmill type offered by the company. By analyzing customer demographics and purchasing behavior, the team can improve recommendations for new buyers. This exploratory data analysis (EDA) will uncover insights into customer preferences and provide data-driven recommendations.

## Product Portfolio
AeroFit offers three treadmill models:
- **KP281**: Entry-level treadmill ($1,500)
- **KP481**: Mid-range treadmill for runners ($1,750)
- **KP781**: Advanced treadmill with premium features ($2,500)

## Dataset Information
The dataset (`aerofit_treadmill_data.csv`) contains the following features:
- **Product** - Purchased treadmill model: KP281, KP481, or KP781
- **Age** - Customer's age in years
- **Gender** - Male/Female
- **Education** - Years of education
- **MaritalStatus** - Single or partnered
- **Usage** - Expected weekly treadmill usage (times per week)
- **Fitness** - Self-rated fitness level (1-5, where 1 = poor, 5 = excellent)
- **Income** - Annual income in US dollars
- **Miles** - Expected weekly miles walked/ran

---

## **Analysis Workflow**

### **1. Data Exploration & Processing**
- Importing and loading the dataset
- Checking dataset shape and structure
- Inspecting data types for each column
- Detecting missing values
- Identifying duplicate records

### **2. Statistical Summary**
- Summarizing categorical and numerical variables
- Interpreting key trends and variations

### **3. Non-Graphical Analysis**
- Counting unique values for categorical features
- Identifying distributions within each category

### **4. Graphical Analysis**
#### **Univariate Analysis:**
- **Numerical Features:**
  - Distribution Plot
  - Count Plot
  - Box Plot
- **Categorical Features:**
  - Count Plot

#### **Bivariate Analysis:**
- Analyzing feature impact on product purchase:
  - **Product vs Gender**
  - **Product vs MaritalStatus**
  - **Product vs Age**

#### **Multivariate Analysis:**
- Creating pairplots to examine feature relationships

### **5. Correlation Analysis**
- Generating a heatmap to show feature correlations
- Extracting key findings from correlation trends

### **6. Outlier Detection**
- Identifying outliers using the IQR method
- Evaluating potential data inconsistencies

### **7. Conditional Probabilities**
- Analyzing purchase probabilities based on demographics:
  - **Product vs Gender:**
    - % of Male customers purchasing a treadmill
    - % of Female customers purchasing KP781
    - Probability of a customer being Female given that Product is KP281
  
  - **Product vs Age:**
    - % of customers aged 20s-30s
  
  - **Product vs Income:**
    - % of low-income customers purchasing a treadmill
    - % of high-income customers purchasing KP781
    - Probability of a high-income customer purchasing KP781

  - **Product vs Fitness:**
    - % of customers with fitness level 5
    - % of fitness level 5 customers purchasing KP781
  
  - **Product vs Marital Status:**
    - % of partnered customers using treadmills

### **8. Actionable Insights & Recommendations**
- Identifying trends in customer preferences
- Making data-driven recommendations for:
  - Marketing strategies
  - Product positioning
  - Pricing adjustments
  - Targeted promotions

---

## **Final Thoughts**
This project will provide in-depth insights into **customer behavior and treadmill preferences**. The goal is to help AeroFit refine its marketing strategies and better serve potential buyers. All findings, visualizations, and recommendations will be clearly documented for easy interpretation.

### 🚀 **Next Steps**
- Conduct A/B testing on promotional strategies
- Develop targeted advertising campaigns based on EDA insights
- Continue data collection for long-term trend analysis

---

## **Repository Structure**
📂 **data/** - Contains `aerofit_treadmill_data.csv`
📂 **notebooks/** - Jupyter notebooks with detailed EDA analysis
📂 **reports/** - Summary of findings and recommendations
📂 **src/** - Python scripts for data preprocessing and visualization
📄 **README.md** - Project description and analysis workflow

### 🔥 **Let's Dive Into the Data!**
