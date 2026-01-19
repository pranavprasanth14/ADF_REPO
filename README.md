# Azure Data Engineering Project

This repository contains an **end-to-end Azure Data Engineering project** implemented using **Azure Data Factory (ADF)**.  
It demonstrates real-world ETL/data integration workflows, including datasets, pipelines, linked services, triggers, and integration runtimes.

---

## 🛠️ Tech Stack
- **Azure Data Factory** – Orchestration of ETL pipelines  
- **Azure Integration Runtimes** – Secure and scalable data movement  
- **Azure DevOps / GitHub** – Version control  
- **Optional:** Databricks, ADLS Gen2, SQL for transformations (if used)

---

## 📁 Repository Structure

ADF_REPO/
├── dataset/ # Dataset definitions
├── factory/ # ADF factory configurations
├── integrationRuntime/ # Integration Runtime settings
├── linkedService/ # Linked service definitions
├── pipeline/ # Pipeline JSON files
├── trigger/ # Trigger definitions
├── README.md # This file
└── publish_config.json # Published pipeline configuration


**Explanation of Sources and Data Flow:**
- **Source Data:** Located in `dataset/` and accessed via linked services defined in `linkedService/`  
- **Transformation:** Pipelines in `pipeline/` use datasets and dataflows to process the data  
- **Storage / Output:** Transformed data is saved to curated zones in ADLS or target systems as defined in `linkedService/`  
- **Automation:** Triggers in `trigger/` schedule the pipelines for regular execution  
- **Runtime:** `integrationRuntime/` manages the compute for moving and transforming data  

---

## 🚀 Project Overview

This project implements a full **data engineering workflow**:

1. **Ingest data** from source datasets  
2. **Transform and clean** data using parameterized ADF pipelines  
3. **Store curated data** in structured zones (ADLS Gen2)  
4. **Schedule pipelines** using triggers  
5. **Manage version control** via GitHub integration  

**Highlights:**
- Parameterized and reusable pipelines  
- Modular datasets and linked services  
- CI/CD-ready with publish configurations  
- Scalable architecture suitable for production environments

---

## 📌 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/pranavprasanth14/ADF_REPO.git

   
💡 Author

Pranav Prasanth – Azure Data Engineering enthusiast, passionate about building scalable, end-to-end cloud data solutions.

#AzureDataFactory #DataEngineering #Azure #ADF #GitHub #CloudData
