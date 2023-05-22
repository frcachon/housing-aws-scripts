# Housing AWS Scripts
.yml scripts used to create AWS stacks (which contain resources such as: VPCs, Lambda functions and Buckets).

stack-MyMainVPC.yml - Creates MyMainVPC and all its related resources.
stack-bucket-csv.yml - Creates the Bucket where the .csv is located.
stack-lambda-CSVUploader.yml - Creates the Lambda function which downloads the CSV file from the bucket and uploads its data into an existing RDS instance (MySQL).

#### Other resources such as the Bucket which hosts the frontend, or the Lambda linking function, were created directly from those services, and are not related to CloudFormation stacks.
