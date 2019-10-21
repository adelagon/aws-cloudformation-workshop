1. Create Cloud9 Environment
2. Create an S3 bucket: aws s3 mb s3://alvin-cloudformation-workshop
3. Create starter template (master-template.yml)
4. Upload templates to S3: aws s3 cp templates/ s3://alvin-cloudformation-workshop --recursive
5. Create EC2 keypair
5. Provision to CloudFormation
6. Now take a look at the VPC dashboard and see the created resources
7. Create the workload template (workload.yml)