# MS_Fabric_MDD - Save at least 50% data engineering effort!
A declarative metadata-driven ETL framework developed using PySpark and Lakehouse and/or data warehouse architecture on Microsoft Fabric, enabling end-to-end data process automation based on configurations defined in YAML files.

Key Features
- Declarative ETL, data engineers define the desired end state of the transformed data, and the ETL tool automatically generates the code to transform the data into that end state
- Align with medallion architecture with customizable bronze, silver and gold layers
- Support the data ingestion of different sources and flat files of csv, text, json, orc, parquet, table, jdbc, excel, xml and dbf
- Support multiple data refresh strategies: full, incremental and backfill
- Support multiple incremental data refresh options: CDF and timestamp, auto fallback to backfill or full data refresh options if in recent not-synced CDF data is purged
- Support multiple data write options: append, merge, overwrite
- Support multiple transformation code: sql, python and notebook
- Support SCD type 2 dimensions
- Built-in micro-batches support for both data ingestion and data transformation
- Built-in rule engine to support data validation and data correctness
- Built-in data lineage and table dependency tracking
- Built-in data orchestration based on notebook DAG

Sample Architecture
![image](https://github.com/user-attachments/assets/6963fe35-e49d-4821-90f1-d92a172e4f67)

![image](https://github.com/user-attachments/assets/b0839581-9cd8-438e-9a67-92bb2602e5bb)
![image](https://github.com/user-attachments/assets/0ffafe32-3550-483e-bb8f-25b7065b50b8)

Sample Demo 
  <img width="1370" height="542" alt="image" src="https://github.com/user-attachments/assets/fe4dd8d1-0d1a-4089-a8de-3d5abf4cabdb" />

- Meta-data Driven ETL - ETL based on configuration
  <img width="1307" height="497" alt="image" src="https://github.com/user-attachments/assets/3b1883ac-9ebd-41d2-81dd-7de093039b38" />

- Full Logging
  <img width="1366" height="582" alt="image" src="https://github.com/user-attachments/assets/35d52788-3425-447b-a2d3-0664b1f69bbb" />

  <img width="1360" height="572" alt="image" src="https://github.com/user-attachments/assets/8958b4a4-bbc6-4c61-9861-1ba8fba31fff" />

  <img width="1377" height="522" alt="image" src="https://github.com/user-attachments/assets/d3e9781d-5b3c-4f7f-8b5d-397cbb3b6fdd" />

- Data Quality
  <img width="1375" height="647" alt="image" src="https://github.com/user-attachments/assets/d36c25eb-a678-4799-8774-638a4f77cb5d" />

Development Demo
- Onboard/ingestion
  <img width="1372" height="666" alt="image" src="https://github.com/user-attachments/assets/99ad4c19-4490-4704-8479-fc695a8cf4d4" />

- Transform/load
  <img width="1314" height="638" alt="image" src="https://github.com/user-attachments/assets/d9f05bca-55e9-4574-a110-d64976321266" />

