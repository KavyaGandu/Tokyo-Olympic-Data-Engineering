# Tokyo Olympic Data Engineering Project

## 📌 Project Overview
This project focuses on end-to-end **data engineering** using **Microsoft Azure** services. The dataset is sourced from Kaggle and processed through various Azure components:

- **Data Extraction**: Pulling data from GitHub.
- **Data Ingestion**: Using Azure **Data Factory**.
- **Storage**: Storing raw and transformed data in **Azure Data Lake Gen2**.
- **Transformation**: Processing and cleaning data with **Azure Databricks (Apache Spark)**.
- **Data Warehousing**: Storing structured data in **Azure Synapse Analytics**.
- **Visualization**: Generating insights using **Power BI / Synapse Analytics**.



## 🚀 Getting Started
### 1️⃣ Prerequisites
- Azure subscription
- Databricks workspace
- Synapse Analytics instance
- Python (3.8+)
- Required Python libraries (`pip install -r requirements.txt`)

### 2️⃣ Deployment Steps
#### **Step 1: Data Ingestion with Azure Data Factory**
1. Create **Azure Data Factory** and set up **pipelines**.
2. Connect **GitHub CSV files** as the source.
3. Set **Azure Data Lake Gen2** as the sink.

#### **Step 2: Data Processing with Azure Databricks**
1. Create a **Databricks workspace** and launch a cluster.
2. **Mount Azure Data Lake Gen2** to access raw data.
3. Perform **data cleaning and transformations** using PySpark.
4. Save processed data back to Azure Data Lake Gen2.

#### **Step 3: Load Data into Azure Synapse Analytics**
1. Create a **Synapse workspace**.
2. Load transformed data into **Synapse tables**.
3. Perform **SQL queries and aggregations**.

#### **Step 4: Data Visualization**
- Use **Power BI** or **Synapse SQL** to generate insights.


## 📌 Key Features
✅ **Automated Data Pipeline** using **Azure Data Factory**  
✅ **Scalable Data Processing** with **Databricks (Apache Spark)**  
✅ **Secure Data Storage** with **Azure Data Lake Gen2**  
✅ **Advanced Analytics** using **Azure Synapse Analytics**  
✅ **Visual Dashboards** with **Power BI / Synapse SQL**

## 🛠️ Technologies Used
- **Azure Data Factory**
- **Azure Data Lake Gen2**
- **Azure Databricks**
- **Apache Spark (PySpark)**
- **Azure Synapse Analytics**
- **SQL, Python**
- **Power BI**

## 📜 License
This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m "Added new feature"`
4. Push to the branch: `git push origin feature-branch`
5. Create a pull request.

## 📬 Contact
For any questions, reach out via [GitHub Issues](https://github.com/KavyaGandu/Tokyo-Olympic-Data-Engineering/issues).

---
🎯 **Goal**: This project demonstrates a **real-world Data Engineering pipeline** using **Azure services**. 🚀
