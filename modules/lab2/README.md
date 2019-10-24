Two ways of Deploying the template:

Option 1 (via console)

Create an S3 Bucket:
aws s3 mb s3://<bucket-name>

Upload Template into createrd bucket
aws s3 cp ec2-with-parameters.yml s3://<bucket-name>

Go to CloudFormation console and launch new stack using S3 url.

Option 2 (via cli)

aws cloudformation deploy --template-file ec2-with-parameters.yml --stack-name my-ec2-stack-3 --parameter-overrides EC2Name=alvinator2