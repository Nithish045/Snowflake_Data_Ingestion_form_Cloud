# Snowflake_Data_Ingestion_form_Cloud:
This project automates ingestion of semi-structured json data stored in azure into a cleaned and structured table in Snowflake which incluedes:

- Automation of json data ingestion stored on Azure Blob-Storage into Snowflake Landing Layer. Creation of Snowpipe
which is auto-triggered using Queue storage and Notification Integration when a new json file is inserted in Blob.
- Scheduling a Task which cleans and structures json data and stores in curated Layer incrementally using a Stream.
