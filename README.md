# 📱 iPhone Sales Analysis

A data science project built with **Python and Jupyter Notebook** to analyze iPhone sales data across different models, storage options, colors, payment methods, and areas in Kolkata.

## 📌 Project Overview

This project performs exploratory data analysis (EDA) on an iPhone sales dataset containing **13,432 records and 12 columns**.

The analysis focuses on understanding:

- Which iPhone models sell the most units
- The highest and lowest priced iPhone models
- Sales by storage capacity
- Sales by color and model combination
- Sales by payment method
- Sales performance across different Kolkata areas

## 🎯 Objectives

The main objectives of this project are to:

1. Analyze iPhone sales performance by model.
2. Identify the maximum and minimum priced iPhone models.
3. Compare sales across different storage capacities.
4. Understand customer payment preferences.
5. Analyze sales performance across different areas.
6. Explore color-wise and model-wise sales patterns.
7. Visualize important sales insights using bar charts.

## 🗂️ Dataset

The dataset used in this project is:

`kolkata_iphone_sales.csv`

### Dataset size

- **Rows:** 13,432
- **Columns:** 12
- **Location:** Kolkata
- **Date range:** September 1, 2025 – August 31, 2026

### Columns

| Column | Description |
|---|---|
| `date` | Sales date |
| `store_id` | Store identifier |
| `area` | Sales area/location |
| `store_type` | Type of store |
| `iphone_model` | iPhone model |
| `storage` | Storage capacity |
| `color` | iPhone color |
| `units_sold` | Number of units sold |
| `unit_price_inr` | Unit price in INR |
| `discount_pct` | Discount percentage |
| `revenue_inr` | Revenue generated in INR |
| `payment_mode` | Payment method used |

## 🛠️ Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical/data visualization

## 🔍 Analysis Performed

### 1. Maximum and Minimum Price Analysis

The project identifies the highest and lowest priced iPhone models.

**Highest-priced model:**
- iPhone 16 Pro Max
- Maximum price: **₹223,800**

**Lowest-priced model:**
- iPhone 13
- Minimum price: **₹53,910**

### 2. Model-wise Sales Analysis

Total units sold were calculated for each iPhone model.

| Rank | Model | Units Sold |
|---:|---|---:|
| 1 | iPhone 16 Pro | 2,088 |
| 2 | iPhone 16 Pro Max | 2,023 |
| 3 | iPhone 14 | 1,998 |
| 4 | iPhone 15 | 1,983 |
| 5 | iPhone 16 | 1,952 |
| 6 | iPhone 15 Plus | 1,948 |
| 7 | iPhone 16 Plus | 1,943 |
| 8 | iPhone 13 | 1,914 |

The **iPhone 16 Pro** recorded the highest total unit sales among the models in the analysis.

### 3. Storage-wise Sales Analysis

Sales were compared across:

- 1TB
- 128GB
- 256GB
- 512GB

The analysis shows that **1TB storage had the highest number of units sold**, while 512GB had the lowest among the four storage categories shown.

### 4. Payment Mode Analysis

The project compares total units sold according to payment method.

Payment methods include:

- Cash
- Credit Card
- Debit Card
- EMI
- UPI

The visualization shows **UPI as the most-used payment mode by units sold**, followed by EMI and Credit Card.

### 5. Area-wise Sales Analysis

Sales were analyzed across 14 Kolkata areas.

| Area | Units Sold |
|---|---:|
| Ballygunge | 810 |
| Behala | 1,776 |
| Camac Street | 775 |
| Dum Dum | 837 |
| Esplanade | 831 |
| Gariahat | 810 |
| Howrah | 811 |
| Lake Town | 825 |
| New Market | 1,563 |
| Park Street | 1,710 |
| Quest Mall Area | 886 |
| Rashbehari | 1,717 |
| Salt Lake (Sector V) | 1,729 |
| South City Mall | 769 |

Among the listed areas, **Behala, Salt Lake (Sector V), Rashbehari, and Park Street** show particularly high unit sales.

### 6. Color-wise Sales Analysis

The project also groups sales by **color and iPhone model** to understand which model-color combinations have higher sales.

Examples from the analysis include:

- Green – iPhone 14: **324 units**
- Black – iPhone 16 Pro: **322 units**
- Blue – iPhone 15: **311 units**
- Blue – iPhone 15 Plus: **308 units**
- Pink – iPhone 16 Pro: **305 units**

## 📊 Visualizations

The project includes bar-chart visualizations for:

- 📊 iPhone model-wise sales
- 📊 Storage-wise sales
- 📊 Payment mode vs total units sold
- 📊 Area-wise iPhone sales
- 📊 Color-wise/model-wise sales

## 💡 Key Insights

Based on the analysis:

- **iPhone 16 Pro** has the highest model-wise unit sales in the dataset.
- **iPhone 16 Pro Max** is the highest-priced model identified.
- **iPhone 13** is the lowest-priced model identified.
- **UPI** is the leading payment mode by total units sold.
- **1TB** storage shows the highest sales among the storage categories analyzed.
- Sales vary considerably across Kolkata areas, with **Behala, Salt Lake (Sector V), Rashbehari, and Park Street** among the stronger-performing locations.
- Color and model combinations also show differences in sales performance.

## 📁 Project Structure

```text
iPhone-Sales-Analysis/
│
├── iPhnSales.ipynb
├── kolkata_iphone_sales.csv
├── README.md
└── images/
    └── charts/
```

> The `images/charts/` folder can be used to store exported visualization images for the GitHub project.

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Suraj1896273/iPhone-Sales-Analysis.git
```

### 2. Open the project folder

```bash
cd iPhone-Sales-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open `iPhnSales.ipynb` and run the notebook cells.

## 📌 Conclusion

This project demonstrates how Python can be used to perform exploratory data analysis on retail sales data. By analyzing model, storage, color, payment mode, price, and location, the project provides a clear view of iPhone sales patterns in Kolkata.

---

## 👤 Author

**Suraj1896273**

Data Science Project – **iPhone Sales Analysis**

⭐ If you find this project useful, feel free to star the repository.
