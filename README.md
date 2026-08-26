
---

# 🛒 **Cloud Retail Analytics Dashboard using Azure & Power BI**

This project demonstrates an **end-to-end cloud analytics workflow** using
**Azure Blob Storage**, **SAS tokens**, **Power BI Desktop**, and **Power BI Service**.

It showcases how real businesses move data to the cloud, transform it, and build interactive dashboards for decision-making.

---

## 📂 **Project Architecture**

```
Superstore Dataset (CSV)
        ↓ Upload
Azure Blob Storage (premkstorage123)
        ↓ Secure Access (SAS URL)
Power BI Desktop
        ↓ Publish
Power BI Service (Cloud Workspace)
        ↓ Pin Visuals
Cloud Dashboard (Superstore Analytics Dashboard)
```

---

## 🚀 **Project Overview**

This project analyzes retail sales data using cloud-based data storage and visualization tools.

### **Key Objectives**

* Store raw data securely in **Azure Blob Storage**
* Generate a **SAS URL** for controlled, temporary access
* Connect Power BI Desktop to **Azure Blob CSV**
* Create an interactive **data storytelling dashboard**
* Publish to Power BI Service and build a cloud dashboard

---

## 🗂️ **Technologies & Tools Used**

| Category       | Tools                                                   |
| -------------- | ------------------------------------------------------- |
| Cloud Platform | Microsoft Azure                                         |
| Storage        | Azure Blob Storage (Storage Account: `premkstorage123`) |
| Access Control | SAS Tokens                                              |
| Visualization  | Power BI Desktop, Power BI Service                      |
| Dataset        | Superstore Sales Dataset (CSV)                          |
| Language       | No coding required (Low-code analytics)                 |

---

## 🧠 **Skills Demonstrated**

* Cloud data storage (Blob Storage)
* Secure data sharing (SAS)
* Power BI dashboard development
* Data modeling in Power BI
* KPI calculation and visualization
* Publishing & managing cloud dashboards
* Report layout and storytelling

---

## 📊 **Dashboard Insights (Superstore Analytics Dashboard)**

The dashboard includes:

### 🔹 **Top-Level KPIs**

* Total Sales
* Total Profit
* Quantity Sold
* Average Discount

### 🔹 **Charts**

* Sales by Category
* Profit by Product
* Sales by Region (Map)
* Sales Over Time (Line Chart)
* Sales by Segment (Donut Chart)

### 🔹 **Filters / Slicers**

*(Only inside report — not pinnable to dashboard)*

* Category
* Region
* Date
* Segment

---

## 🏗️ **Step-by-Step Workflow**

### **1️⃣ Upload Data to Azure Blob Storage**

* Created Storage Account → `premkstorage123`
* Created container → `datasets`
* Uploaded **superstore.csv**
* Generated **Blob SAS URL**

---

### **2️⃣ Connect Power BI to Azure Blob**

Power BI → Get Data → **Web**
Paste the SAS URL → load data securely from cloud.

---

### **3️⃣ Build the Report in Power BI Desktop**

Created:

* KPI cards
* Time series line chart
* Region map
* Category bar chart
* Profit matrix
* Segment donut chart
* Slicers

---

### **4️⃣ Publish to Power BI Service**

Signed in with organizational email →
Published to **My Workspace**.

---

### **5️⃣ Create Cloud Dashboard**

Pinned visuals from report into:

```
Superstore Analytics Dashboard
```

Organized visuals in KPI → Charts → Trends layout.

---

## 📸 **Screenshots (Add after uploading)**

You can upload screenshots here later:

```
/screenshots/dashboard.png
/screenshots/report.png
/screenshots/azure_storage.png
/screenshots/powerbi_publish.png
```

---

## 🧩 **Future Improvements**

* Automate refresh using Azure Data Factory
* Store cleaned data in Azure SQL
* Build ETL pipeline
* Add advanced DAX measures
* Add anomaly detection using Azure ML

---

## 🧑‍💻 **Author**

**Premkumar**
Final-year B.Tech – AI & Data Science
Vel Tech Multi Tech Engineering College, Chennai

---

## ⭐ **If you like this project**

Consider giving the repo a ⭐ star and following for more cloud analytics projects.

---

