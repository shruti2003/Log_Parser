# ⚡ Log Parser - AMD Silicon Testing Automation  

## 📌 Project Overview  
The **Log Parser** is a fully automated **log processing and analysis pipeline** designed to support **manual testing of new AMD silicon chips**. This system automates workload testing, log parsing, and performance data visualization, ensuring efficient and structured reporting for **AMD performance engineers**.  

Note: Unable to add the code details to respect the companies data / privacy

### 🔍 Key Features  
✅ **ADLS Log Dumping** - Automated log collection from **Azure Data Lake Storage (ADLS)**  
✅ **Workload Automation** - Runs **MLC, DRAM Latency, STREAM** workloads on new silicon chips  
✅ **Log Parsing & Data Processing** - Extracts and structures test results using **PySpark**  
✅ **Big Data Manipulation** - Handles large-scale logs efficiently in **Databricks**  
✅ **Power BI Integration** - Converts parsed data into interactive dashboards  
✅ **Automated Execution** - Runs on a **scheduled cron job** every 30 minutes  

---

## 🏗️ Technologies Used  
- **Azure Data Lake Storage (ADLS)** for log storage  
- **Databricks & PySpark** for **big data processing**  
- **Power BI** for **data visualization & reporting**  
- **Python** for **log parsing & automation**  
- **Cron Jobs** for **automated scheduling**  

---

## 🚀 Workflow  
1. **ADLS Dumps Logs** - Workloads generate logs, automatically stored in **ADLS**  
2. **Databricks Processing** - Logs are parsed, structured, and analyzed using **PySpark**  
3. **Pipeline Execution** - The parsed results are **transferred to Power BI** for reporting  
4. **Scheduled Automation** - A **cron job runs every 30 minutes**, ensuring **continuous updates**  

---

## 🎯 Accomplishments  
🏆 **Became a critical application for AMD's silicon testing**  
🏆 **Replaced manual testing workflows with a fully automated system**  
🏆 **Enhanced efficiency for performance engineers by providing structured test results**  

---
