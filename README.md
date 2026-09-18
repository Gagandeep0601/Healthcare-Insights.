🚀 **Healthcare Analytics | Azure Data Factory + Azure SQL + Power BI**

Built an Azure-based healthcare analytics pipeline using ADF, Azure SQL, and Power BI with watermark-driven incremental loads and MERGE/Upsert processing for automated reporting.



🔹 **What I built:**
• Centralized healthcare data pipeline integrating EHR, Billing, HR, PMS, and Finance data
• Automated ETL workflows using **Azure Data Factory**
• **Watermark-based incremental loading** to process only new and updated records
• Staging and **MERGE/Upsert** logic using Azure SQL stored procedures
• Power BI dashboards for healthcare KPIs and operational reporting
• **RBAC and Row-Level Security (RLS)** for secure data access
• Data quality checks including validation, reconciliation, and duplicate handling

🔹 **How I built it:**
**Source Systems → Azure Blob Storage → Azure Data Factory → Azure SQL Database → Power BI**

The incremental workflow follows:

**Old Watermark → New Watermark → IF Condition → Copy Delta → MERGE/Upsert → Update Watermark**

<img width="1312" height="1199" alt="image" src="https://github.com/user-attachments/assets/3510a418-827a-4654-a7aa-4c082e74cb5c" />


🔹 **Key outcome:**
The solution automated data ingestion and reporting, reduced unnecessary full-load processing, centralized healthcare data, and enabled more timely and reliable Power BI insights.

🛠️ **Tools & Technologies:**
Azure Data Factory | Azure SQL Database | Azure Blob Storage | Power BI | SQL | SSMS | Azure Monitor | Key Vault | RBAC | RLS | Jira

📊 This project helped me strengthen my experience in **data engineering, BI development, data quality, cloud data integration, and analytics reporting**.

#Azure #AzureDataFactory #AzureSQL #PowerBI #DataAnalytics #DataEngineering #HealthcareAnalytics #BusinessIntelligence #SQL #ETL #CloudComputing #DataIntegration #MicrosoftAzure

