Project Folder Worldbank contains below folders


WorldBank 
- Data(master)
- x23425237_Bharathi_Ramapatnam_Dagster (All the code artifacts for Bharathi(Dagster only)

------ below are the files related to ETL flow built in JN
ETL1.ipynb(master)
ETL2.ipynb(master)
ETL3.ipynb(master)


-------- Excel file containing the steps taken for each ETL flow
ETLFlow.xlsx


------- some re-usable functions 
functions.ipynb(master)




------- images files used for markdown
map.jpg
map.eap.jpg



--------- these files contain visuals built 

x23425237_Bharathi_Ramapatnam_Visuals(master)


-----  Project Objective: 
The objective of this project is to:

* Query the World Bank API to extract semi-structured data (e.g., in JSON format) and store it in MongoDB.

* Implement an ETL (Extract, Transform, Load) process to extract the required data from MongoDB, transform it as needed, and load it into PostgreSQL for further analysis.

* ETL orchestration will be managed through Dagster, enabling automation, monitoring, and scheduling of the ETL workflows.

* Import economic work-related data (e.g., workforce participation, employment rates) from CSV and XML files into PostgreSQL.

* Combine both XML and CSV data, merge it with the data in PostgreSQL, and build meaningful visualizations to analyze the data.

