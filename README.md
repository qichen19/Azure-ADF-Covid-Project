## Overview
This Azure Data Factory project is designed to collect and transform COVID-related data from various sources, including websites and Azure Blob Storage. The transformed data is then stored in Azure Data Lake Storage Gen2 and Azure SQL Database. Finally, Power BI is employed to generate insightful reports and visualizations based on the processed data.

## Solution Architecture
![image](https://github.com/qichen19/Azure-ADF-Covid-Project/assets/57600028/a6a2443e-c900-475c-8ad1-a1e7e0a49d09)

## Key Components
1. Data Ingestion<br />
The project leverages Azure Data Factory's capabilities to efficiently gather COVID-related data from diverse sources, ensuring a comprehensive dataset.

2. Data Transformation<br />
Collected data undergoes transformation processes within Azure Data Factory to ensure consistency, cleanliness, and compatibility with downstream analytics and reporting requirements.

3. Data Storage<br />
Transformed data is persisted in Azure Data Lake Storage Gen2 and Azure SQL Database, allowing for scalable and efficient storage solutions based on the characteristics of the data.

4. Data Publishing & Reporting<br />
Power BI is integrated into the pipeline to create dynamic and interactive reports. These reports provide valuable insights into the collected and transformed COVID data, enabling stakeholders to make informed decisions.


## Resources
All project-related resources are available in the Azure-ADF-Resources repository (https://github.com/qichen19/Azure-ADF-Resources/tree/master). Specifically:

* COVID-related data can be found in the 'covid data from ecdc' folder.
* Population data is located within the 'population' folder.
* Data used for lookup operations is stored in the 'lookup' folder.
* Notebooks for data transformation using Databricks are in the 'databricks notebook' folder.
* Scripts for HDInsight data transformation can be accessed from the 'hdinsight script' folder.
* SQL scripts for creating a database within Azure SQL are contained in the 'SQL' folder.

## Pipelines


## Usage
Clone the repository and set up Azure Data Factory with the necessary configurations.<br />
Execute the data pipeline to collect, transform, and store COVID-related data.<br />
Utilize Power BI to generate and visualize reports based on the processed data.

## PowerBI Report
Report in PDF format: https://github.com/qichen19/Azure-ADF-Resources/blob/master/powerBI/EU%20Covid%20Report.pdf <br />
Report: https://github.com/qichen19/Azure-ADF-Resources/blob/master/powerBI/EU%20Covid%20Report.pbix


## Contributing
Contributions to enhance data collection, transformation processes, or reporting features are welcome. Follow standard Git workflows and submit pull requests.

## License
This project is licensed under the MIT License.



## PowerBI Report



