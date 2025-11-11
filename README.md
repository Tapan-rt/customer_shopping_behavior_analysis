## 📊 Data Analytics Project

## 🧭 Overview

This project demonstrates a complete **end-to-end data analytics workflow** — from loading raw data and performing **Exploratory Data Analysis (EDA)** to creating a **Power BI dashboard** and a **final presentation using Gamma**.
The goal is to extract meaningful insights from data using **Python, SQL, and Power BI**, and to present the findings in a clear, visual, and actionable manner.

---

## 📂 Dataset

* **Source:** Kaggle
* **Format:** CSV
* **Size:** Approx. 3900 rows × 18 columns
* **Description:** The dataset contains information about customer ID, customer data, item purchased, review rating, shipping type, payment method , etc.
* **Key Features:**

  * `Category` – type of product
  * `Review Rating` – customer rating given to the product
  * `Location` – geographical region
  * `Payment Method` – mode of payment
  * `Purchase amount` – number of units purchased by customer

---

## 🛠️ Tools and Technologies

| Category      | Tools Used                                       |
| ------------- | ------------------------------------------------ |
| Programming   | Python (Pandas, NumPy, Matplotlib, Seaborn)      |
| Database      | PostgreSQL / MySQL / SQL Server                  |
| Visualization | Power BI                                         |
| Presentation  | Gamma App                                        |
| Other         | Jupyter Notebook, SQL Workbench / pgAdmin / SSMS |

---

## 🚀 Steps Performed

## 1. Data Loading

* Imported dataset using **Pandas**.
* Verified data types and loaded the file into a **DataFrame**.

### 2. Data Cleaning

* Handled **missing values**, **duplicates**, and **inconsistent data**.
* Standardized column names and formats.
* Converted data types where necessary.

### 3. Exploratory Data Analysis (EDA)

* Used **Matplotlib** and **Seaborn** for visual exploration.
* Found patterns, outliers, and correlations.
* Generated statistical summaries (mean, median, mode, variance, etc.).

### 4. SQL Analysis

* Imported cleaned data into **SQL database** (PostgreSQL/MySQL/SQL Server).
* Performed **SQL queries** for aggregation, joins, and insights extraction.
* Example queries:

```sql
select gender, SUM(purchase_amount) as revenue
from customer
group by gender;

```

### 5. Power BI Dashboard

* Connected the cleaned dataset / SQL database to Power BI.
* Created **interactive visuals** showing KPIs, trends, and comparisons.
* Included filters (slicers) for subscription status, gender, category, and shipping type.

### 6. Report and Presentation

* Summarized findings and visuals into a **professional report**.
* Built an engaging presentation in **Gamma App** highlighting:

  * Business problem & objectives
  * Key insights from EDA & SQL
  * Visual storytelling through Power BI

---

## 📈 Dashboard

* **Tool:** Microsoft Power BI
* **Main Visuals:**

  * Average Purchase Amount
  * Average Review Rating
  * Revenue by Category
  * Sales by Category
  * % of customers by subscription status

---

## 🧾 Results & Insights

* Identified top-performing regions and time periods.
* Found key drivers of sales growth and underperforming categories.
* Provided actionable recommendations to improve decision-making.

---

## ▶️ How to Run the Project

### Prerequisites

* Python 3.8+
* PostgreSQL / MySQL / SQL Server
* Power BI Desktop
* Gamma account (for final presentation)

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/data-analytics-project.git
   cd data-analytics-project
   ```
2. Install required Python packages:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:

   ```bash
   jupyter notebook Data_Analysis.ipynb
   ```
4. Import the cleaned dataset into your SQL database.
5. Run SQL queries provided in `queries.sql`.
6. Open the Power BI file (`dashboard.pbix`) to view the dashboard.
7. Review the final presentation via the Gamma link or PDF.

---

## 🧑‍💻 Author

**Tapan Tiwari**
📧 [tapan.r.tiwari@gmail.com]

---

