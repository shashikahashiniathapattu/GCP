Overview of Solution - 
1. Setup Big Query in Google Cloud. Create data set and table according to the JSON file columns. 
2. Create service Account - After that created new service account under the API and Credentials. Created JSON type private key , downloaded it and saved in computer folder.
3. Load data into table using Python Code – Python code has been done in Visual studio Code. Install libraries in Google Cloud SDK Shell using following commands. 
I. Pip install –upgrade google-cloud.
II. Pip install – upgrade google-cloud-bigquery.
III. Pip install – upgrade google-cloud-storage.
After that import credentials, table id and row data using python query and execute it to load data into the Big Query table. 

how to run the project locally - 
•	Download a service account key file locally. Save it as JSON
•	To define an environment variable GOOGLE_APPLICATION_CREDENTIAL that points to the absolution path of the key file on our workstation.
•	Run the application.
