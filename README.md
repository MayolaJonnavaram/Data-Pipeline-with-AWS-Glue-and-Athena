Data Pipeline with AWS Glue and Athena
•	Created an S3 input bucket to store CSV data and an S3 output bucket for storing processed results.
•	Utilized AWS Glue to create a database and configure a table crawler, which automatically crawled and cataloged the data in the input bucket.
•	Defined the input bucket location and set the correct schema for processing.
•	Launched Amazon Athena and configured the output bucket location in settings, selecting the appropriate database.
•	Executed SQL queries in Athena to process the data and stored the results in CSV format in the output S3 bucket.
•	Managed the entire project as an IAM user, ensuring the required admin access to S3, Glue, and Athena for seamless execution of the data pipeline and proper access control.

Services Used:
AWS Athena, Amazon S3, SQL, AWS GLUE & IAM 
