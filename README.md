# NYC Taxi Dataset Analysis using PySpark on Databricks

## 📌 Project Overview

This project demonstrates how to process and analyze customer and product data using **Apache Spark (PySpark)** on **Azure Databricks**. The goal is to clean, process, and derive **key business insights (KPIs)** from raw CSV files provided by the client.

---

## 📁 Dataset Description

### 1. Customer Data
- `Product_id`
- `Customer_id`
- `Order_date`
- `Location`
- `Source_order`

### 2. Product Data
- `Product_id`
- `Product_name`
- `Price`

Both datasets are stored in CSV format and are uploaded into the Databricks environment.

---

## 📊 Business Requirements

The client wants to understand their business better using analytics. The following KPIs are to be calculated:

- ✅ Total amount spent by each customer
- ✅ Total amount spent by each product category
- ✅ Monthly sales totals
- ✅ Yearly and quarterly sales
- ✅ Total number of orders by category
- ✅ Top 5 ordered items
- ✅ Overall top ordered item(s)
- ✅ Frequency of customer visits
- ✅ Sales by country (location)
- ✅ Sales by order source (online, offline, etc.)

---

## ⚙️ Technologies Used

- **Apache Spark (PySpark)**
- **Azure Databricks**
- **Jupyter Notebook**
- **CSV file format**
- **Databricks Dashboard**

---

## 🛠️ Setup Instructions

1. **Upload CSV files** to Databricks via the "Tables" section.
2. **Create a Databricks Cluster** under the "Compute" section.
3. **Open the Notebook** (`NYC_Taxi_Dataset_Analysis.ipynb`) and attach it to the cluster.
4. **Run the Notebook** cells to:
   - Load data into DataFrames
   - Clean and transform the data
   - Perform aggregations and analytics
5. **Create Visualizations** and build a **dashboard** from the results.

---

## 📈 Output

All computed KPIs are visualized in an interactive **Databricks dashboard**, giving stakeholders easy access to critical business metrics.

---

## 🧑‍💻 Author

- Prepared by: *Your Name*
- Tools used: Databricks, PySpark, Jupyter Notebook

---

## 📬 Contact

For any queries or suggestions, please contact: [your-email@example.com]

