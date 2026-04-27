# E-Commerce Data Analytics: SQL & Python
**Unlocking Business Intelligence from Brazilian E-Commerce Trends**

## Project Overview
This project performs an end-to-end data analysis of a Brazilian e-commerce dataset. By combining **SQL** for complex data extraction and **Python** for advanced analytics and visualization, the project identifies key growth drivers, seasonal trends, and customer behavior patterns across nearly 100,000 orders.

## Project Structure
```text
ecommerce-analytics-project/
│
├── data/                       # Dataset source files
│   ├── customers.csv
│   ├── sellers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── payments.csv
│   └── products.csv
│
├── notebooks/                  # Interactive analysis
│   ├── python_code.ipynb       # Exploratory Data Analysis (EDA)
│   └── sql_code.ipynb          # SQL Query logic
│
├── outputs/                    # Processed data
│   └── cleaned_data.csv        # Unified dataset for modeling
│
└── README.md                   # Project documentation
```

## Dataset Overview
| File | Description | Records |
| :--- | :--- | :--- |
| **customers.csv** | Geographic and unique ID details for users | 99,441 |
| **orders.csv** | Timestamps and status for every transaction | 99,441 |
| **order_items.csv** | Details on products, prices, and shipping per order | 112,650 |
| **payments.csv** | Payment types and installment breakdown | 103,886 |
| **products.csv** | Category names and physical specifications | 32,951 |
| **sellers.csv** | Seller location and ID information | 3,095 |

## Tech Stack
* **Database**: SQLite (Structured querying and window functions)
* **Data Manipulation**: Pandas & NumPy
* **Visualization**: Matplotlib & Seaborn
* **Environment**: Jupyter Notebook / Google Colab

## Key Analytical Queries

### **Level 1: Basic Insights**
* **Market Reach**: Identified **4,119 unique cities** served by the platform.
* **Order Volume**: Successfully tracked **45,101 orders** placed in the 2017 fiscal year.
* **Payment Behavior**: Found that **49.42%** of all orders are paid using installments.
* **Geography**: Confirmed **SP (São Paulo)** as the primary hub with 41,746 customers.

##  **Visualisation**
![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/1.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/2.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/3.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/4.png)


### **Level 2: Intermediate Analytics**
* **Seasonality**: Identified January 2018 as a peak period with **6,288 orders**.
* **Revenue Leaders**: Ranked product categories by revenue; **Health & Beauty** dominates the market share at **9.26%**.
* **Seller Performance**: Ranked the top-performing seller with a total revenue of **₹2,29,472**.

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/5.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/6.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/7.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/8.png)

### **Level 3: Advanced Strategic Intelligence**
* **YoY Growth**: Analyzed a massive **12,000%+ revenue surge** between 2016 and 2017.
* **Customer Retention**: Calculated a **2.31% retention rate**, highlighting the need for future loyalty programs.
* **Moving Averages**: Utilized SQL window functions to calculate the moving average of order values to track spending volatility.

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/9.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/10.png)

![image alt](https://github.com/vnandini879/E---Commerce-sells-and-customer-analytics-/blob/4cbba7e66577c911c0f32e6e95aa8565a1728572/11.png)

## Key Business Insights
1.  **The "São Paulo" Dominance**: Over 40% of the customer base is concentrated in one state, suggesting a need for logistical optimization in that region.
2.  **Credit Reliance**: Nearly half of the transactions involve installments, indicating that flexible payment options are a critical driver for high-ticket sales.
3.  **Revenue Concentration**: Categories like **Health & Beauty**, **Watches/Gifts**, and **Bed/Table/Bath** generate the majority of platform revenue.
4.  **Retention Opportunity**: The low repeat-purchase rate (2.31%) suggests that while the platform is excellent at acquiring new customers, there is significant untapped potential in re-engagement marketing.

## How to Use
1.  **Clone**: `git clone https://github.com/vnandini879/ecommerce-analytics-project.git`
3.  **Environment**: Install dependencies via `pip install pandas matplotlib seaborn`.
4.  **Explore**: Run `python_code.ipynb` to view the visual trends or `sql_code.ipynb` to inspect the relational database logic.

   
## Project By
* **Name**: Nandini Verma
* **Tools**: Python, SQLite, Pandas, Matplotlib, Seaborn
* **Platform**: Google Colab + GitHub
