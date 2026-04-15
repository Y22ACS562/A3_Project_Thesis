#  Vendor Performance Analytics System

##  Authors  
S.Thaslim (Y22ACS562)
s.Vasavi (Y22ACS550)
M.Avinash(Y22ACS506)
R.Abhinay (L23ACS612)

---

##  Implementation  
**GitHub Repository:**  
Vendor Performance Analytics System Implementation:https://github.com/Y22ACS562/Vendor-Performance-Analysis.git

---

##  Overview  
The Vendor Performance Analytics System is a data-driven solution designed to analyze and evaluate vendor performance using data analytics and machine learning techniques.  

This system processes multiple datasets such as purchases, sales, inventory, vendor invoices, and purchase prices to generate meaningful insights. It helps organizations identify high-performing vendors, detect low-performing vendors, and support better decision-making through interactive dashboards.  

---

##  Key Features  
- Vendor Performance Analysis based on sales, profit, and inventory  
- Vendor Segmentation (Low / Medium / High Performance)  
- Risk Classification of Vendors  
- K-Means Clustering for pattern identification  
- Data Cleaning, Transformation, and Integration  
- CSV Output Generation for reporting  
- Interactive Dashboard using Power BI  
- Business Insights for decision-making  

---

##  System Architecture  

The system consists of the following major modules:

### 1. Data Ingestion  
Loads multiple datasets such as purchases, sales, inventory, vendor invoices, and purchase prices into the system.

### 2. Data Processing  
Performs data cleaning, handling missing values, removing duplicates, and feature engineering.

### 3. Data Integration  
Combines datasets using SQL operations to create a unified dataset (vendor_sales_summary).

### 4. Analysis & Modeling  
Applies analytical techniques and K-Means clustering to segment vendors and identify trends.

### 5. Output Generation  
Generates processed CSV files and analytical results.

### 6. Visualization  
Displays insights using Power BI dashboards for better understanding and decision-making.

---

##  Tech Stack  
- Programming Language: Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- Database: SQLite  
- Visualization Tool: Power BI  
- Development Tools: Jupyter Notebook, VS Code  

---

##  Model Details  
- Algorithm Used: K-Means Clustering  
- Purpose: Vendor segmentation and pattern identification  
- Evaluation Basis: Cluster grouping and performance trends  
- Output: Vendor categories (Low, Medium, High), Risk Levels  

---

##  Output  
- Vendor Performance Categories  
- Vendor Risk Segmentation  
- Sales, Profit, and Inventory Insights  
- CSV files for reporting  
- Power BI Dashboard with interactive visualizations  

---

##  How to Run  

pip install -r requirements.txt  
python main.py  

Steps:
1. Load datasets into the system  
2. Run preprocessing and integration scripts  
3. Generate output CSV files  
4. Import CSV files into Power BI  
5. View dashboard insights  

---

##  Future Scope  
- Integration with real-time data sources  
- Advanced machine learning models for prediction  
- AI-based recommendation system for vendor selection  
- Deployment as a web or mobile application  
- Real-time alerts and notifications  
- Sales forecasting and demand prediction  
