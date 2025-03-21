# 🚗 Uber Data Analytics Project

## 📌 Overview
This project analyzes **Uber trip data** to extract insights on **user demand, peak hours, revenue trends, and trip efficiency**. The project is built using **Mage for ETL**, **Google Cloud Platform (GCP) for data storage and querying**, and **BigQuery for large-scale analytics**. The analysis helps optimize Uber’s operations by providing actionable insights.

---

## 🚀 Key Features
- **🛠 Data Engineering with Mage:** Set up automated ETL pipelines for Uber trip data.
- **☁️ Cloud-Based Analytics:** Stored and queried data using **GCP’s BigQuery**.
- **📊 Data Visualization:** Built interactive dashboards with **Looker Studio**.
- **🔍 Demand & Revenue Insights:** Analyzed trip data to identify **peak hours, route efficiency, and revenue trends**.
- **📈 Predictive Analysis (Future Scope):** Developed a framework for forecasting Uber trip demand.

---

## 📂 **Project Structure & Implementation**
### **1️⃣ Data Collection & Storage**
- **Raw Data Source:** The dataset was obtained from **Uber trip logs**.
- **Cloud Storage:** The data was uploaded to **Google Cloud Storage (GCS)** for scalable and secure access.
- **File Format:** The dataset is stored as `.csv` for easy integration with BigQuery.


### **2️⃣ ETL (Extract, Transform, Load) Pipeline**
- **Tool Used:** **Mage** (A modern data pipeline tool)
- **Data Cleaning Steps:**
  - Removed missing values.
  - Standardized timestamp formats.
  - Converted categorical data into meaningful labels.
- **Data Transformation:** Processed data before loading into BigQuery.


### **3️⃣ Data Warehousing & Querying**
- **Storage Tool:** **Google BigQuery**
- **Purpose:**
  - Stored structured Uber trip data for easy querying.
  - Enabled fast analysis of **millions of records** using SQL queries.


### **4️⃣ Exploratory Data Analysis (EDA)**
- **Visualization Tools:** **Matplotlib, Seaborn, Looker Studio**
- **Insights Discovered:**
  - Identified **peak booking hours** and busiest regions.
  - Analyzed **trip duration vs. fare pricing**.
  - Found **most profitable Uber routes**.


### **5️⃣ Dashboard & Reporting**
- **Tool Used:** **Looker Studio (formerly Data Studio)**
- **Dashboard Features:**
  - **Trip Demand Trends:** Heatmaps for peak hours.
  - **Revenue Analysis:** Graphs showing earnings by location & time.
  - **Route Optimization:** Visual representation of busiest routes.

## 📈 Key Insights
- 🚀 Peak Demand: Uber rides increase by 35% during weekends and peak between 6-9 PM.
- 💰 Revenue Trends: Higher revenue in Manhattan & Brooklyn, with avg. trip fare increasing by 20% at night.
- 🏙️ Busiest Routes: Most Uber rides occur between airports & downtown business areas.




