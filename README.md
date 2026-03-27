# MS_Fabric_MDD 
## production-ready, save at least 50% data engineering effort!
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
  <img width="1928" height="858" alt="image" src="https://github.com/user-attachments/assets/a8d46eb4-b271-459c-af9c-6263d0354840" />
  ![image](https://github.com/user-attachments/assets/b0839581-9cd8-438e-9a67-92bb2602e5bb)
  ![image](https://github.com/user-attachments/assets/0ffafe32-3550-483e-bb8f-25b7065b50b8)

Sample Demo 
  <img width="2000" height="169" alt="image" src="https://github.com/user-attachments/assets/545957a5-2046-4f49-a3c4-aed3f7e51219" />
  <img width="1938" height="477" alt="image" src="https://github.com/user-attachments/assets/ccc8f1ca-73d2-4d2c-9a9a-9624354a8e8e" />
  <img width="1307" height="497" alt="image" src="https://github.com/user-attachments/assets/3b1883ac-9ebd-41d2-81dd-7de093039b38" />

- Onboard/Ingestion
  <img width="1261" height="609" alt="image" src="https://github.com/user-attachments/assets/38734dbc-676f-4d82-a220-2bdd445935cb" />

- Transform/Load
  <img width="1249" height="571" alt="image" src="https://github.com/user-attachments/assets/b2777152-0342-4b58-8dca-297f402ce199" />
  <img width="995" height="591" alt="image" src="https://github.com/user-attachments/assets/e6264cd7-f071-4ae0-a535-3f6ece7fb826" />

- Data Validation
  <img width="1120" height="590" alt="image" src="https://github.com/user-attachments/assets/b2b9319b-8b55-4012-82fa-1968412e2409" />
  <img width="1375" height="647" alt="image" src="https://github.com/user-attachments/assets/d36c25eb-a678-4799-8774-638a4f77cb5d" />
  
- Full Logging
  <img width="1360" height="572" alt="image" src="https://github.com/user-attachments/assets/8958b4a4-bbc6-4c61-9861-1ba8fba31fff" />
  <img width="1377" height="522" alt="image" src="https://github.com/user-attachments/assets/d3e9781d-5b3c-4f7f-8b5d-397cbb3b6fdd" />
  <img width="1366" height="582" alt="image" src="https://github.com/user-attachments/assets/35d52788-3425-447b-a2d3-0664b1f69bbb" />

Development Activities
- Onboard/ingestion
  1. Define the bronze table
  2. Prepare the configurations
  3. Test the data ingestion
  <img width="1372" height="666" alt="image" src="https://github.com/user-attachments/assets/99ad4c19-4490-4704-8479-fc695a8cf4d4" />

- Transform/load
  1. Define the gold table
  2. Prepare the configurations
  3. Compile the business logic
  4. Test the data load
  <img width="1314" height="638" alt="image" src="https://github.com/user-attachments/assets/d9f05bca-55e9-4574-a110-d64976321266" />

- Monitoring & Auditing
  <img width="1600" height="883" alt="image" src="https://github.com/user-attachments/assets/488aa09f-3acd-415f-a17a-012af75bcc15" />

