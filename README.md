# MNC-Growth-and-Workforce-Analytics-Using-Python
A data-driven analysis of revenue growth, industry performance, employee expansion, and business trends.

# 🏢 MNC Growth & Workforce Analytics Using Python 📊

## 🔍 1. Project Overview

This project focuses on analyzing company growth, revenue performance, workforce trends, industry performance, and geographical distribution using Python.

The analysis is performed on the **Inc. 5000 Companies Dataset**, which contains information about companies featured on the 2019 Inc. 5000 list.

The project involves data cleaning, data transformation, feature engineering, Exploratory Data Analysis (EDA), statistical analysis, and data visualization to identify meaningful business patterns and insights.

🎯 **Main Goal:** To understand how companies perform in terms of revenue growth, employee expansion, industry contribution, and geographical presence using data analytics.

---

## 📂 2. Dataset Information

🟢 **Dataset Name:** Inc. 5000 Companies Dataset  
🟢 **Original Source:** [Maven Analytics – Data Playground](https://mavenanalytics.io/data-playground)  
🟢 **Domain:** Finance / Business Analytics  
🟢 **File Format:** CSV  
🟢 **Number of Records:** 502 Rows  
🟢 **Original Attributes:** 14 Columns  
🟢 **Dataset Coverage:** Companies featured on the 2019 Inc. 5000 list  
🟢 **Founding Year Range:** 1909–2015  
🟢 **Geographical Coverage:** 43 States, 293 Cities, and 54 Metropolitan-area labels  

The dataset includes information about company names, revenue, revenue growth, industry, location, founding year, and workforce size.

---

## 🎯 3. Project Objectives

The project focuses on seven major business objectives:

🔵 **1. Analyze Company Growth**
- Identify companies with the highest revenue growth percentage.
- Understand differences in company growth performance.

🟣 **2. Compare Industry Performance**
- Identify industries generating the highest total revenue.
- Compare workforce size across industries.

🟢 **3. Evaluate Workforce Growth**
- Identify companies with the highest employee growth.
- Compare previous and current workforce figures.

🟠 **4. Analyze Geographical Distribution**
- Identify states and cities with the highest number of companies.
- Compare company revenue across geographical locations.

🔴 **5. Study Revenue and Growth Trends**
- Analyze the relationship between company revenue and revenue growth percentage.
- Understand whether higher-revenue companies also experience higher growth.

🟡 **6. Analyze Revenue per Employee**
- Calculate revenue generated per employee.
- Identify companies generating higher revenue relative to their workforce.

🔵 **7. Study Company Age and Business Trends**
- Analyze companies based on their founding years.
- Compare revenue growth among newer and older companies.
- Identify industries with higher and lower representation.

---

## 🛠️ 4. Tools & Technologies

| Technology | Usage |
|---|---|
| 🐍 Python | Programming and data analysis |
| 🐼 Pandas | Data cleaning, manipulation, and analysis |
| 🔢 NumPy | Numerical calculations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical charts and visualizations |
| 📓 Google Colab | Writing and executing Python code |
| 📁 Jupyter Notebook | Interactive data analysis |

---

## 🧹 5. Data Preprocessing & Feature Engineering

The dataset was cleaned and transformed to make it suitable for analysis.

### 🟢 Data Cleaning
- Checked the dataset structure and data types.
- Identified missing and duplicate records.
- Handled missing values and inconsistent entries.
- Replaced unknown values where required.
- Standardized text columns by removing unwanted spaces.
- Renamed columns for better readability.

### 🔵 Data Transformation
- Converted revenue values from text format into numeric values.
- Converted required columns into appropriate data types.
- Rounded revenue growth percentages for better readability.
- Standardized company and location-related information.

### 🟣 Feature Engineering

Created additional features to support deeper analysis:

| New Feature | Description |
|---|---|
| Employee_Change | Difference between current and previous workforce |
| Employee_Growth_Percentage | Percentage change in employee count |
| Company_Size | Categorized companies as Small, Medium, or Large |
| Company_Age | Calculated company age using 2015 as the reference year |
| Revenue_Per_Employee | Revenue generated relative to the current workforce |

These features helped analyze company expansion, workforce performance, and revenue efficiency.

---

## 📊 6. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure, distribution, and characteristics of the dataset.

🔹 Checked the number of rows and columns.  
🔹 Examined column names and data types.  
🔹 Identified missing values and duplicate records.  
🔹 Calculated descriptive statistics.  
🔹 Analyzed numerical and categorical variables.  
🔹 Examined company revenue and workforce distribution.

---

## 📈 7. Statistical Analysis

Statistical techniques were used to understand the distribution and variation of company performance.

🟢 **Measures of Central Tendency**
- Mean
- Median
- Mode

🔵 **Measures of Dispersion**
- Variance
- Standard Deviation

🟣 **Distribution Analysis**
- Skewness
- Kurtosis

🟠 **Outlier Detection**
- Box plots
- Interquartile Range (IQR) method

These techniques helped identify variations in revenue growth and understand the impact of unusually high or low values.

---

## 📉 8. Data Visualization

Different visualization techniques were used to identify patterns, trends, and relationships.

### 1. Univariate Analysis
- 📊 Histograms
- 📊 Count plots
- 📦 Box plots

### 2. Bivariate Analysis
- 🔵 Scatter plots
- 📊 Bar charts
- 🔗 Correlation analysis

### 3. Multivariate Analysis
- 🌡️ Correlation heatmap
- 📊 Pair plots
- 📈 Grouped analysis
- 📋 Pivot tables

Each visualization was supported by an interpretation and business insight to explain its relevance.

---

## 💡 9. Key Findings & Business Insights

The analysis generated the following important findings:

🟢 **Company Growth**
- Revenue growth varies considerably across companies.
- A few companies show exceptionally high growth percentages.
- Median growth is useful alongside the mean because extreme values influence the average.

🔵 **Industry Performance**
- The Health industry contributes the highest total revenue among the industries analyzed.
- Industry-wise revenue and workforce distribution help compare business performance.

🟣 **Workforce Analysis**
- Most companies belong to the Small company category.
- Larger workforce size does not necessarily indicate higher employee growth.
- Workforce expansion varies across companies.

🟠 **Geographical Distribution**
- California has the highest number of companies among the states analyzed.
- California also contributes the highest total revenue among the top 10 states.
- New York City has the highest company count among the cities analyzed.

🔴 **Revenue and Growth Relationship**
- Revenue and revenue growth percentage have a very weak positive correlation of approximately **0.07**.
- Higher-revenue companies do not necessarily experience higher revenue growth.

🟡 **Revenue per Employee**
- Revenue per employee helps compare revenue generation relative to workforce size.
- It provides an indication of revenue efficiency, but does not directly measure profit or individual employee productivity.

🟤 **Company Age and Business Trends**
- Companies were compared based on their founding years and age groups.
- Revenue growth patterns vary across company age groups.
- Industry representation differs across the dataset.

### 🎯 Overall Business Insight

The analysis shows that company revenue, revenue growth, workforce size, and employee growth are different performance indicators. Businesses should evaluate these factors separately to understand company performance and make informed decisions.

---

## 🧠 10. Types of Analysis Performed

🔵 **1. Descriptive Analysis**
- Summarized company revenue, workforce, and growth.
- Calculated statistical measures.
- Identified top-performing companies and industries.

🟣 **2. Diagnostic Analysis**
- Examined relationships between revenue and revenue growth.
- Compared workforce size with employee growth.
- Studied differences across company age groups and locations.

🟢 **3. Predictive Analysis**
- Discussed possible future enhancements using regression and machine learning techniques.
- No predictive model was implemented in the current analysis.

🟠 **4. Prescriptive Analysis**
- Suggested business recommendations based on the findings.
- Highlighted areas such as workforce planning, revenue efficiency, and geographical expansion.

---

## 🚀 11. How to Run This Project

Follow these steps to execute the project:

**Step 1: Clone the Repository**

```bash
git clone https://github.com/your-username/your-repository-name.git
```

**Step 2: Navigate to the Project Folder**

```bash
cd your-repository-name
```

**Step 3: Install Required Libraries**

```bash
pip install pandas numpy matplotlib seaborn
```

**Step 4: Open the Notebook**

- Open the `.ipynb` file using Jupyter Notebook or Google Colab.
- Upload the dataset CSV file if it is not included in the repository.
- Update the dataset file path in the notebook if necessary.

**Step 5: Run the Notebook**

Execute the notebook cells in sequence, starting with data loading and continuing through preprocessing, feature engineering, statistical analysis, and visualizations.

---

## 📁 12. Project Files

The repository can be organized as follows:

```text
MNC-Growth-and-Workforce-Analytics/
│
├── 📓 MNC_Growth_&_Workforce_Analytics_using_Python.ipynb
│
├── 📂 Dataset/
│   └── Modified_Company_Growth_Dataset.csv
│
├── 📂 Documentation/
│   └── Project_Documentation.pdf
│
├── 📂 Visualizations/
│   └── Charts_and_Graphs/
│
└── 📄 README.md
```

## 🔮 13. Future Enhancements

The project can be improved further through the following enhancements:

🟢 Include more recent company datasets to analyze current business trends.

🔵 Compare company performance across multiple years.

🟣 Add additional business attributes such as profit, expenses, investment, and market share.

🟠 Apply regression analysis to study factors influencing company growth.

🔴 Implement machine learning models for revenue or workforce trend prediction.

🟡 Develop an interactive dashboard using Power BI or Tableau.

---

## 🏁 14. Conclusion

The **MNC Growth & Workforce Analytics Using Python** project demonstrates how Python can be used to clean, transform, analyze, and visualize company data.

Through Exploratory Data Analysis, statistical analysis, and data visualization, the project identifies important patterns in company revenue, growth, workforce, industry performance, and geographical distribution.

The findings provide a better understanding of business performance and demonstrate how data analytics can support informed business decision-making.

---

## 👩‍💻 15. Project Skills Demonstrated

- 🐍 Python Programming
- 🐼 Data Cleaning and Data Transformation
- 🔧 Feature Engineering
- 📊 Exploratory Data Analysis (EDA)
- 📈 Statistical Analysis
- 🎨 Data Visualization
- 🔍 Business Insight Generation
- 💡 Analytical and Problem-Solving Skills

---

Author:
Angeline E
Emerging Data Analyst
