# -Building-an-automated-data-pipeline-for-sales-data-in-Google-Cloud

This project showcases the development of a fully automated data pipeline for sales data leveraging Google Cloud Platform (GCP) services. The pipeline commences with a Python Flask web portal for uploading sales data files (CSV, Excel), which are subsequently stored in a Google Cloud Storage (GCS) bucket. A trigger is then activated, invoking a Google Cloud Function to process and load the data into BigQuery for analytics and storage. The Cloud Function utilizes the BigQuery client library to execute the data load, while also handling errors and exceptions using try-except blocks. Furthermore, Looker Studio is integrated to create interactive and insightful dashboards and reports for data visualization, providing real-time sales data insights. By integrating these GCP services, the project enables a seamless, efficient, and automated data pipeline for sales data, from upload to visualization.
 
![image](https://github.com/user-attachments/assets/bec99b25-6f3f-4d90-a49d-8001a36b1b77)

Architecture 
![image](https://github.com/user-attachments/assets/20965a52-69de-4e10-9f87-6452d18c482d)


