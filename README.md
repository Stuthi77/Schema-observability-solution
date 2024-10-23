# Schema-observability-solution
1. Collecting all table lineage details including the created_by details of of (schema changed table,notebook,job,dashboard,query,model,pipeline,file),authorised group details and authorised individual user details using API calls and in-built databricks tables and storing all details in downstream_audit delta table
2. Sending consolidated email to required authorized groups,users and owners about all schema changes recorded the in the schema_registry delta table of particular table (input details: catalog_name,schema_name,table_name) and their authorization for to get the email
Emp Id: 4273
