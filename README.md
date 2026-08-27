# restaurant-branch-performance-eda
# 🍽️ Restaurant Branch Performance — Exploratory Data Analysis

##  Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a Restaurant Branch Performance dataset using **Python, Pandas, NumPy, and Matplotlib**.

The analysis explores restaurant performance from different perspectives, including **customers, revenue, profit, marketing spend, staff count, delivery time, customer ratings, branches, regions, store types, and promotions**.

The goal of this project is to identify patterns, relationships, and meaningful business insights from the data using fundamental EDA techniques.

---

##  Objectives

The main objectives of this analysis are to:

* Understand the structure and characteristics of the dataset.
* Perform data-quality checks for missing values and duplicates.
* Generate descriptive and summary statistics.
* Analyze the distributions of important numerical variables.
* Compare restaurant performance across different branches.
* Compare performance across regions and store types.
* Analyze the relationship between promotions and business performance.
* Use correlation analysis to identify relationships between numerical variables.
* Extract meaningful, data-driven business observations.

---

##  Technologies & Libraries Used

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Jupyter Notebook / Google Colab**

---

##  Analysis Performed

### 1. Dataset Overview

The dataset was first examined to understand:

* Number of rows and columns
* Column names
* Data types
* Missing values
* Duplicate records
* Unique values

### 2. Descriptive Statistics

Summary statistics were generated for numerical variables to understand:

* Mean
* Median
* Standard deviation
* Minimum and maximum values
* Quartiles

Categorical variables were also examined to understand their frequency and distribution.

### 3. Distribution Analysis

Histograms were used to explore the distributions of important variables such as:

* Customers
* Revenue
* Profit
* Marketing Spend
* Staff Count
* Average Delivery Time
* Customer Rating

### 4. Branch Performance

Restaurant branches were compared using metrics such as:

* Average customers
* Average revenue
* Average profit
* Marketing expenditure
* Staff count
* Delivery time
* Customer rating

### 5. Regional Analysis

Restaurant performance was compared across different regions to identify variations in:

* Customer volume
* Revenue
* Profit
* Marketing spend
* Delivery time
* Customer ratings

### 6. Store Type Analysis

Different store types were compared based on their:

* Customers
* Revenue
* Profit
* Marketing spend
* Delivery time
* Customer ratings

### 7. Promotion Analysis

The analysis also examined whether restaurant records associated with different promotion categories showed differences in:

* Customers
* Revenue
* Profit
* Customer ratings

Missing promotion values were treated as **No Promotion** for this descriptive comparison.

### 8. Correlation Analysis

A Pearson correlation matrix was created to examine relationships between numerical variables.

The analysis particularly focused on relationships involving:

* Revenue
* Profit
* Customers
* Average Bill
* Marketing Spend
* Operating Cost
* Food Cost
* Customer Rating
* Delivery Time

Correlation was used to identify **associations**, not causal relationships.

---

##  Key Findings

The EDA produced several meaningful observations:

1. The dataset contains **restaurant branch performance records** with information covering customers, revenue, costs, profit, marketing, staffing, delivery, ratings, and other business factors.

2. **Revenue has a strong positive relationship with Profit**, indicating that higher-revenue records generally tend to be associated with higher profits.

3. Other financial and operational variables, including **Food Cost, Operating Cost, Customers, and Average Bill**, also show important relationships with Profit.

4. Restaurant performance varies across branches, with some branches achieving substantially higher average profitability than others.

5. Regional differences are visible in average restaurant performance, suggesting that location may be an important factor when evaluating branch results.

6. **Premium stores** show substantially higher average customer volume and profitability compared with other store types in the dataset.

7. **Customer Rating has a relatively weak relationship with Profit**, suggesting that a higher rating alone does not necessarily correspond to higher financial performance.

---

##  Business Insights

The analysis suggests that restaurant profitability is more closely connected to **revenue, customer volume, average bill, and cost-related factors** than to customer ratings alone.

Differences between branches, regions, and store types also indicate that restaurant performance should not be evaluated using a single metric. A combination of **financial, operational, and customer-related metrics** provides a more complete picture.

These findings could be useful for identifying high-performing branches, understanding operational differences, and determining areas that may require further investigation.

> **Important:** Correlation indicates association between variables and does not prove that one variable causes another.

---

##  Project Structure

```text
restaurant-branch-performance-eda/
│
├── README.md
├── Restaurant_Branch_Performance_EDA_Day13.ipynb
└── Day13_Restaurant_Branch_Performance_Dataset.csv
```

---

##  How to Run the Project

### Option 1 — Google Colab

1. Open Google Colab.
2. Upload `Restaurant_Branch_Performance_EDA_Day13.ipynb`.
3. Upload the dataset CSV file.
4. Run the notebook cells sequentially.

### Option 2 — Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib
```

Then open the notebook using Jupyter Notebook or JupyterLab and run the cells.

---

##  Project Type

**Exploratory Data Analysis (EDA)**

This project was completed as part of a **Day 13 Data Science learning/assignment activity**, focusing on fundamental data analysis concepts using Pandas.

---

##  Skills Demonstrated

* Python
* Pandas
* NumPy
* Data Cleaning
* Data Exploration
* Descriptive Statistics
* Data Aggregation
* GroupBy Analysis
* Distribution Analysis
* Data Visualization
* Correlation Analysis
* Business Insight Generation
* Exploratory Data Analysis

---

##  Note

This project is intended for **educational and portfolio purposes**. The conclusions are based on the available dataset and represent descriptive observations rather than causal claims.

