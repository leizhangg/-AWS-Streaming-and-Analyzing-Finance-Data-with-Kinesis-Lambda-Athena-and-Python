# Streaming and Analyzing Stock Price with AWS Kinesis, Lambda, Athena, and Python

The tasks of this project are provisioning a Lambda function to generate near real time finance data records for interactive querying, generating a real time data pipeline for finance data records, and analyzing data based on requests.

The tasks include 3 parts:
  - Infrastructure
    - Data Transformer
    - Data Collector
    - Data Analyzer
    - Data Visualization
  - Data Collection 
  - Data Visualization

### Infrastructure

The first step is to provision infrasturcture needed for this project,including:
- Kinesis Delivery stream.    
  As we want to generate real time
- Lambda function 
- S3 Bucket
- AWS Glue
- AWS Athena 
