# Uber-DataEngg
Data Engineering project with end to end implementation.
<br><br>
<b>Step 1: Data Collection</b> <br>
Dataset used: https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv
More info about dataset can be found here:
Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
<br><br>
<b>Step 2: Understanding the data and creating a Data Model</b>
Data Model:
<img width="929" alt="Screenshot 2023-11-01 at 8 25 08 PM" src="https://github.com/im-aditi/Uber-DataEngg/assets/64597243/a95be645-a6b4-4487-a853-1f63088ce6e5">
<br><br>
Link: https://app.diagrams.net/#G1cpJ7ZjPlVsL3VrL5dxiFmJbyjGoe2Mn0
<br><br>
<b>Step 3: Create a Data Flow Diagram</b><br><br>
<img width="452" alt="Screenshot 2023-12-20 at 3 54 57 PM" src="https://github.com/im-aditi/Uber-DataEngg/assets/64597243/f37a5a01-b64c-442c-a162-bdba9c6e3d79">
<br><br>
<b>Step 4: Create a Postgres RDS on AWS.</b>
<img width="1360" alt="Screenshot 2023-12-20 at 3 04 57 PM" src="https://github.com/im-aditi/Uber-DataEngg/assets/64597243/2a6d1aae-0504-4a9b-a972-bd9d87f829f4">

<b>4.1</b> Connect to it using python (File: Uber.ipynb) <br>
<b>4.2</b> Create Dimension and Fact Tables and populate them (File: DML Statements)

<b>Step 5: Perform ETL on the data using AWS Glue</b> <br>
AWS Glue is a fully managed extract, transform, and load (ETL) service offered by Amazon Web Services (AWS). It's designed to help users prepare and transform their data for analytics and data-driven applications. It supports transforming data using Apache Spark ETL jobs, enabling complex data transformations and processing at scale. Also, it allows users to define workflows using AWS Glue Studio or Apache Spark that automate and schedule ETL jobs, ensuring data pipelines run efficiently.

AWS Glue simplifies the process of preparing and transforming data, making it suitable for various data analytics, machine learning, and data warehousing applications within the AWS ecosystem.
<br><br>
<img width="1369" alt="image" src="https://github.com/im-aditi/Uber-DataEngg/assets/64597243/3f7949f3-f7e2-498d-93e5-8d4321534f92">
<br><br>
File: ETL-AWS Glue.md

<b>Step 6: Perform Analysis using Amazon Redshift</b><br>
Amazon Redshift is a fully managed, cloud-based data warehousing service provided by Amazon Web Services (AWS). It's designed for handling large-scale analytics and data warehousing workloads. Data in Redshift is stored in a columnar format, optimizing query performance by only reading the columns necessary for a query, reducing I/O and improving compression. It utilizes a clustered architecture with nodes running in parallel to process and distribute queries across multiple nodes for faster query execution.

File: Redshift.md
<br><br>
<img width="856" alt="image" src="https://github.com/im-aditi/Uber-DataEngg/assets/64597243/6324d594-e139-4a41-af6d-b9b3047b8cc2">

<br><br><br>
Credits: https://www.youtube.com/watch?v=WpQECq5Hx9g
